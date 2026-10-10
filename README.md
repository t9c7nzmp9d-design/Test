# Würfel – App für iPad

Eine Würfel-App mit wählbarer Seitenzahl (4, 6, 8, 10, 12, 20, 100), umgesetzt als
Web-App (PWA), die auf dem iPad wie eine normale App installiert werden kann und
auch offline funktioniert.

## Auf dem iPad installieren

1. Die App muss über HTTPS erreichbar sein, z. B. mit GitHub Pages:
   Repository → *Settings* → *Pages* → Branch auswählen → *Save*.
2. Die Seite auf dem iPad in **Safari** öffnen.
3. Auf das **Teilen**-Symbol tippen → **„Zum Home-Bildschirm“** → **Hinzufügen**.

Danach startet die App vom Home-Bildschirm im Vollbild, ohne Browserleiste.

## Dateien

- `index.html` – die App
- `manifest.webmanifest` – App-Name, Icons, Vollbildmodus
- `sw.js` – Service Worker für Offline-Betrieb
- `icons/` – App-Icons
