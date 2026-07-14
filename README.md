# Praxisabrechnungsassistent Pro – Web-App 1.0

## Funktionen
- iPad-optimiertes Dashboard
- Behandlungserfassung
- Labor- und CAD/CAM-Aufträge
- offene Arbeiten und Patientenhinweise
- Tagesprotokoll
- PDF-Ausgabe über den Browser-Druckdialog
- lokale Speicherung im Browser
- PWA-/Offline-Grundstruktur

## Testen
Die App sollte über einen kleinen Webserver bereitgestellt werden.

Beispiel auf einem Computer:
`python -m http.server 8000`

Danach:
`http://localhost:8000`

Für den iPad-Test eignet sich GitHub Pages, Netlify oder ein lokaler Server im selben WLAN. Anschließend in Safari öffnen und über „Teilen“ → „Zum Home-Bildschirm“ installieren.

## Grenzen
- keine serverseitige Datenbank
- keine Mehrplatzsynchronisierung
- keine Praxissoftware-Anbindung
- Browser-Spracherkennung ist auf Safari/iPadOS nicht zuverlässig; die iPad-Diktierfunktion im Textfeld ist die sichere Alternative


## GitHub-Pages-Vorbereitung

Dieses Paket enthält zusätzlich:

- `.nojekyll`
- GitHub-Actions-Workflow zur automatischen Veröffentlichung
- `netlify.toml`
- Schritt-für-Schritt-Anleitungen für GitHub Pages und Netlify

Für GitHub muss `index.html` direkt im Hauptverzeichnis des Repositorys liegen.
