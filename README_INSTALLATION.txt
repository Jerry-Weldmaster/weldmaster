WeldMaster PWA 1.2 – Installation auf dem iPad

1. Den gesamten Inhalt dieses ZIP-Archivs auf einem HTTPS-Webserver veröffentlichen (index.html, manifest.webmanifest, sw.js, Icons im selben Ordner).
2. Die HTTPS-Adresse in Safari auf dem iPad öffnen.
3. Teilen > Zum Home-Bildschirm > Hinzufügen wählen.
4. App bei bestehender Verbindung einmal starten, damit der Offline-Cache aufgebaut wird.
5. WPS-Daten über „Alle exportieren“ regelmäßig als JSON sichern.

WICHTIG:
- Eine lokale HTML-Datei oder das bloße Entpacken des ZIP auf dem iPad installiert KEINE PWA.
- Ohne HTTPS-Hosting ist der Service Worker nicht nutzbar (localhost ist eine Entwickler-Ausnahme).
- Die Daten bleiben im lokalen Browser-/App-Speicher. Löschen der Websitedaten oder App kann sie entfernen. Keine geräteübergreifende Synchronisierung.
- Der PDF-Export verwendet die Browser-Druckfunktion. Das finale Drucklayout ist noch nicht fachlich und visuell freigegeben.
- Die WPS ist ein Entwurf und nicht automatisch technisch qualifiziert.
