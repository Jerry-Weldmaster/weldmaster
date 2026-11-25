WeldMaster 4.1 – Dynamische Nahtzeichnungen
Stand: 25. November 2026
Grundlage: EXAKTE index.html aus deinem GitHub-Repository
Jerry-Weldmaster/weldmaster, Version 4.0 (Commit 098e25056f4a79a6cdb222a542d07254db87f25d).

VOR DEM UPDATE: DATEN SICHERN
1. In der laufenden WeldMaster-App: „Alle WPS exportieren“ (JSON).
2. WPQR-Verwaltung separat exportieren (JSON).
3. Firmengeräte-Verwaltung separat exportieren (JSON).
4. Sicherungskopien der bestehenden sieben Dateien aufbewahren.

NEU IN 4.1
- Dynamische SVG-Nahtzeichnungen für I-, V-, X-, Y-Stumpfnaht und Kehlnaht.
- Schweißnaht und sichtbarer Einbrand orange (60 % transparent); Grundwerkstoffe grau.
- X-Stumpfnaht oben und unten gespiegelt, graue Spitzen bleiben Teil des Grundwerkstoffs.
- Kehlnaht am Eckstoß: zwei getrennte Bleche mit waagrechter Stoßfuge.
- Kehlnahtgröße als a- oder z-Maß wählbar; das jeweils andere Maß wird berechnet.
- Zeichnungen passen sich an Blechdicke, Öffnungswinkel, Wurzelspalt und Steghöhe an.
- Dasselbe SVG-Prinzip wird für Editor-Vorschau und WPS-PDF verwendet.
- Alle Funktionen der Version 4.0 bleiben enthalten: Firmengeräte,
  Schweißername, Schweißseiten, Badsicherung, Wurzelschutzgas, Qualifizierung,
  Werkstoffkataloge, WPQR-Verwaltung und WeldMaster-WPS-Ausdruck.

INSTALLATION (GitHub Pages)
1. Dieses ZIP entpacken.
2. ALLE SIEBEN Dateien aus dem ZIP in das ROOT-Verzeichnis des Repositories
   Jerry-Weldmaster/weldmaster, Branch main, hochladen und gleiche Namen ersetzen.
3. Änderungen mit Commit bestätigen.
4. In Safari WeldMaster neu laden. Bei alter Anzeige App schließen und erneut öffnen.
5. WPS-Speicher, Geräteverwaltung, alle fünf Nahtbilder und PDF-Vorschau prüfen.

HINWEISE
- Der Browser speichert WPS und Gerätedaten lokal. Daten bleiben beim Update
  in der Regel erhalten, solange dieselbe URL genutzt wird und die Browserdaten
  nicht gelöscht wurden. Eine Sicherung ist trotzdem erforderlich.
- a = z / sqrt(2) gilt für die theoretische gleichschenklige 90°-Kehlnaht
  mit gerader Nahtoberfläche. Gewölbte Nahtränder sind schematisch.
- Einbrand ist eine schematische Illustration, keine reale Einbrandmessung.
- Die WPS-Ausgabe ist weiterhin ein Entwurf, keine normative Freigabe.
- Das Update veröffentlicht sich NICHT selbst bei GitHub.
