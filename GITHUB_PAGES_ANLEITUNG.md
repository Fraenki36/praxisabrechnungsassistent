# Veröffentlichung mit GitHub Pages auf dem iPad

## Vorbereitung
1. Erstelle ein kostenloses GitHub-Konto.
2. Öffne GitHub in Safari.
3. Lege ein neues Repository an, zum Beispiel `praxisabrechnungsassistent`.
4. Wähle **Public**. GitHub Pages ist damit am einfachsten nutzbar.

## Dateien hochladen
1. Öffne das neue Repository.
2. Tippe auf **Add file** → **Upload files**.
3. Entpacke dieses ZIP-Paket vorher in der Dateien-App.
4. Lade **den Inhalt des Ordners** hoch, nicht den übergeordneten Ordner.
5. Bestätige unten mit **Commit changes**.

Wichtig: `index.html` muss direkt im Hauptverzeichnis des Repositorys liegen.

## GitHub Pages aktivieren
1. Öffne im Repository **Settings**.
2. Wähle links **Pages**.
3. Unter **Build and deployment** wähle:
   - Source: **GitHub Actions**
4. Der vorbereitete Workflow veröffentlicht die Seite automatisch.
5. Nach kurzer Zeit erscheint unter **Pages** die Webadresse.

Typische Adresse:
`https://DEIN-BENUTZERNAME.github.io/praxisabrechnungsassistent/`

## Auf dem iPad als App nutzen
1. Öffne die veröffentlichte Adresse in Safari.
2. Tippe auf **Teilen**.
3. Wähle **Zum Home-Bildschirm**.
4. Bestätige mit **Hinzufügen**.

Die Anwendung erscheint anschließend wie eine App auf dem Home-Bildschirm.

## Neue Version hochladen
1. Öffne das Repository.
2. Ersetze die geänderten Dateien.
3. Bestätige mit **Commit changes**.
4. GitHub Pages veröffentlicht die neue Version automatisch.

## Hinweis zur Testphase
Die App speichert eingegebene Testdaten nur lokal im jeweiligen Browser. Daten werden nicht zwischen mehreren Geräten synchronisiert.
