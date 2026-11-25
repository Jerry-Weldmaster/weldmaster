WeldMaster 4.2 – Einheitliche Nahtzeichnungen fuer Rohr und Blech
Stand: 25. November 2026
Ausgangspunkt: WeldMaster 4.1, GitHub Jerry-Weldmaster/weldmaster,
Commit 17cd852d04593f2b4bfbdf71c3ee3316ce3384d7.

NEU IN 4.2
- Die fertigen SVG-Stumpfnahtzeichnungen I, V, X und Y verwenden bei
  Rohr und Blech denselben Renderer und dieselbe Grundgeometrie.
- Bei Rohr entspricht die Dicke in der Nahtskizze der eingegebenen
  Rohrwandstaerke, bei Blech der Blechdicke.
- Eine stark aufgetragene Nahtueberhoehung wird bei duennen
  Wandstaerken in der SCHEMATISCHEN Skizze flacher gezeichnet.
- Die eingegebenen Werte der Naht- und Wurzelueberhoehung bleiben
  UNVERAENDERT in der WPS und im PDF-Feld, da sie technisch massgebend sind.
- Gleiche Konturen, Farben, Einbrand und Proportionen in Live-Vorschau
  und WPS-PDF; keine separate Rohrquerschnitt-Grafik.
- Die 3D-Vorschaubilder der Schweisspositionen bleiben rohrspezifisch,
  da sie die jeweilige Schweissposition darstellen, nicht den Nahtquerschnitt.
- Cache-Version des Service Workers auf v4-2 erhoeht.

BESTEHENDE FUNKTIONEN
Die Inhalte und Funktionen aus WeldMaster 4.1 bleiben erhalten:
I-, V-, X-, Y-Stumpfnaht, Kehlnaht am Eckstoss mit a-/z-Mass,
Schweissgeraeteverwaltung, WPQR, Werkstoffkataloge, lokale WPS-Verwaltung,
WPS-PDF, Firmenlogo und zusaetzliche Dokumentationsfelder.

INSTALLATION (GitHub Pages, iPad/Safari)
1. Vorher alle WPS und WPQR sowie Firmengeraete separat als JSON sichern.
2. ZIP entpacken und alle sieben Dateien im Root des Repositories
   Jerry-Weldmaster/weldmaster, Branch main, hochladen und ersetzen.
3. Auf GitHub Commit bestaetigen und GitHub Pages neu laden.
4. In Safari bei alter Anzeige aktualisieren, ggf. installierte PWA neu starten.
5. Test: Blech-I-Naht und Rohr-I-Naht bei gleicher Dicke und gleichen
   Nahtparametern vergleichen. Die SVG-Bilder muessen identisch sein.
6. Test: Bei einer Rohrwandstaerke von 2 mm und eingetragener
   Nahtueberhoehung von 1,5 mm muss die Orange-Kontur flach aussehen,
   waehrend der WPS-Wert weiterhin 1,5 mm lautet.

SICHERHEIT / QUALIFIZIERUNG
Die Zeichnung ist schematisch und nicht massstaeblich. Sie darf keine
fachliche Pruefung der eingetragenen Werte ersetzen. Keine automatische
normative Freigabe, WPQR- oder Produktzulassungspruefung.
