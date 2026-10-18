# Karte Zweiter Weltkrieg

Interaktive Multiperspektiven-Karte zum Zweiten Weltkrieg (1937–1945) mit Zeitleiste, historischen Ereignissen und Zeitzeug*innen-Quellen.

Online: https://geschichtefuerdiegegenwart.github.io/Karte-Zweiter-Weltkrieg/

## Technik

- `index.html` ohne Build-Prozess, Font Awesome lokal in `vendor/fontawesome`. Öffnen per Doppelklick funktioniert.
- Leaflet 1.9.4 (BSD-2-Clause) und Leaflet.markercluster 1.5.3 (MIT) sind direkt eingebettet.
- Kartenkacheln: OpenStreetMap (online über GitHub Pages). Beim Öffnen per Doppelklick (`file://`) werden CARTO-Kacheln (ebenfalls OpenStreetMap-Daten) genutzt, weil die OSM-Server Anfragen ohne Herkunftsangabe ablehnen.
- Ohne Internet erscheint im Kartenbereich eine Fehlermeldung; Marker, Zeitleiste und Quellen funktionieren weiter.
- Alternative: lokal starten mit `python3 -m http.server` im Ordner und `http://localhost:8000` öffnen.

Die Fassung vor der Reparatur liegt unter `archiv/fassung-vor-reparatur.html`.

## Quellen

Alle Zitate sind mit der Fundstelle abgeglichen (Stand Oktober 2026). Die Daten erzeugt `tools/zeitzeugen-geprueft.py`; die Prüfung der früheren 79 Einträge steht in `PRUEFBERICHT.md`, die alten Daten in `archiv/zeitzeugen-vor-pruefung.json`.
