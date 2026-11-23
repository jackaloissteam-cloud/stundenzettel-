# Stundenzettel

Einzelplatz-Stundenzettel als einzelne HTML-Datei, ohne Server und ohne Abhängigkeiten.

## Funktionen
- Monatsblatt im Layout der Vorlage (Tag, von, bis, Pause, Arbeitszeit, Tagesverdienst, Bemerkung)
- Jahresübersicht Januar bis Dezember mit Übertrag (Saldo gegenüber 43 Std./Monat)
- Stunden zu 13,90 € bis zur Grenze, darüber zu 12,00 € (Sätze und Grenze einstellbar)
- Suche über alle gespeicherten Monate
- Export: Monat als Excel-Tabelle, Jahr als CSV, Drucken/PDF, Sicherung als JSON

## Nutzung
- Lokal: `index.html` im Browser öffnen.
- Online: GitHub Pages aktivieren (Settings → Pages → Branch `main`, Ordner `/ (root)`).
  Die App ist dann unter `https://<name>.github.io/<repo>/` erreichbar.

## Daten
Die Einträge liegen nur im Browser des jeweiligen Geräts (`localStorage`, Schlüssel `stundenzettel-v1`).
Zum Übertragen auf ein anderes Gerät: **Sichern** (JSON) und dort **Laden**.
