# ENOLA Prototyp

Klickbarer UI/UX-Prototyp für die Messnetzverwaltung von ENOLA: einheitliche Listen, Karte, Diagramme und Detailseite einer Messstelle. Läuft komplett im Browser, ohne Server.

**Online ansehen:** https://yashdeepsingh407.github.io/enola-prototyp/

## Was echt ist und was Demo
- Echt: 1049 Grundwassermessstellen aus dem Geodatenportal Berlin (WFS, Lizenz dl-zero-de/2.0) und Wetterstationen mit Stundenwerten vom Deutschen Wetterdienst über Bright Sky (CC BY 4.0, Quelle: Deutscher Wetterdienst).
- Demo: Grundwasser-Zeitreihen, Aufgaben, Fotos, Dateien, Ausrüstung, Nutzer und Benachrichtigungen. Eingaben bleiben nur im Browser und sind nach dem Neuladen weg.
- Ohne Internet fällt der Prototyp auf Demodaten zurück.

## Lokal starten
```bash
python3 -m http.server 8791
```
Dann http://localhost:8791 öffnen.

## Hinweis
Gestaltungs-Konzept, keine offizielle ENOLA-Software. Die Kartenkacheln stammen von BKG TopPlusOpen (dl-de/by-2-0) und OpenStreetMap.
