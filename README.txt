EDDIE EICHHORN – AR WEBSITE PROTOTYP

Dateien
- index.html: Landingpage + 3D-Vorschau
- ar.html: markerbasierte Web-AR-Kameraansicht
- assets/eddie.glb: aus dem gelieferten STL konvertiertes 3D-Modell
- assets/eddie-marker.png: druckbarer AR-Marker
- assets/pattern-eddie.patt: Tracking-Muster für AR.js

STARTEN
1. Ordner auf einen HTTPS-Webserver hochladen (Kamera-Zugriff benötigt HTTPS).
2. Alternativ lokal testen: im Ordner `python3 -m http.server 8000` starten und http://localhost:8000 öffnen.
3. Marker `assets/eddie-marker.png` auf einem zweiten Gerät anzeigen oder ausdrucken.
4. Auf dem Smartphone `ar.html` öffnen und Kamerazugriff erlauben.

WICHTIG
Die JavaScript-Bibliotheken A-Frame, AR.js und model-viewer werden über CDNs geladen. Für den Prototyp ist daher eine Internetverbindung erforderlich.
Das gelieferte STL enthält keine Texturen; deshalb wird das Modell als einfarbige, warme Eddie-Figur dargestellt. Für die finale Optik empfiehlt sich ein texturiertes GLB/GLTF-Modell.
