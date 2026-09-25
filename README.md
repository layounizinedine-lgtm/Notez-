# Notez

Eine schlichte Karteikarten-App zum Selberbefüllen, inspiriert von Anki.

- **Themen & Unterkategorien:** beliebig tief verschachtelt (z. B. Arabisch › Einkaufen › Vokabeln).
- **Wortliste:** Wort — Übersetzung, optional mit Beispielsatz. Arabische Schrift wird automatisch rechts-nach-links dargestellt.
- **Karteikarten:** Antwort aufdecken und bewerten:
  Schlecht → 1 Min · Geht so → 15 Min · Gut → 6 Std · Perfekt → 1 Tag.
- **Quiz:** Wort sehen, aus 4 Antworten die richtige wählen (10 Fragen pro Runde).
- **Menü:** Dunkel / Hell / System, App-Farbe, Abfragerichtung, Backup speichern und laden.

Alle Daten bleiben lokal im Browser (localStorage). Die App funktioniert offline.

## Starten

Keine Installation nötig. `index.html` über einen beliebigen Webserver ausliefern, z. B.:

```sh
python3 -m http.server 8000
```

Dann <http://localhost:8000> öffnen. Auf dem Handy über „Zum Home-Bildschirm hinzufügen“ als App installieren.

Am einfachsten dauerhaft online: **GitHub Pages** aktivieren (Settings › Pages › Branch auswählen).
