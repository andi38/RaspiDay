## Arduino mit Ethernet Shield als Web Server zur Grafikausgabe

Die folgenden Dateien müssen hierfür auf der SD Karte im Namensformat 8.3 sein
* /index.htm (alias plot.ly.html)
* /plotly.js (alias plotly-latest.min.js)

### Erfahrungsbericht
Es funktioniert eingeschränkt. Grundsätzlich ist die Funktionalität da, 
aber das Laden der plotly-latest.min.js Datei (2,2 MB groß) dauert 12min, also unpraktikabel. Denn der Arduino schiebt die Dateien
zeichenweise von SD über den Ether. Schade. 
