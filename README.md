# Karte Zweiter Weltkrieg

Interaktive Multiperspektiven-Karte zum Zweiten Weltkrieg (1937–1945) mit Zeitleiste, historischen Ereignissen und Zeitzeug*innen-Quellen.

Online: https://geschichtefuerdiegegenwart.github.io/Karte-Zweiter-Weltkrieg/

## Technik

- Eine einzige Datei `index.html`, ohne Build-Prozess. Öffnen per Doppelklick funktioniert.
- Leaflet 1.9.4 (BSD-2-Clause) und Leaflet.markercluster 1.5.3 (MIT) sind direkt eingebettet.
- Kartenkacheln: OpenStreetMap (online über GitHub Pages). Beim Öffnen per Doppelklick (`file://`) werden CARTO-Kacheln (ebenfalls OpenStreetMap-Daten) genutzt, weil die OSM-Server Anfragen ohne Herkunftsangabe ablehnen.
- Ohne Internet erscheint im Kartenbereich eine Fehlermeldung; Marker, Zeitleiste und Quellen funktionieren weiter.
- Alternative: lokal starten mit `python3 -m http.server` im Ordner und `http://localhost:8000` öffnen.

Die Fassung vor der Reparatur liegt unter `archiv/fassung-vor-reparatur.html`.
