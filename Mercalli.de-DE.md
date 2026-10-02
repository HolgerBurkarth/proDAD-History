<p align="center">
  <a href="Mercalli.md"><img src="https://img.shields.io/badge/EN-English-dd9900?style=for-the-badge" alt="English"></a>
  <img src="https://img.shields.io/badge/DE-Deutsch-cccccc?style=for-the-badge" alt="Deutsch (aktuell)">
</p>


# Mercalli – Industriestandard & Weltreferenz für Videostabilisierung, Linsenentzerrung und CMOS-Korrektur

## Einleitung

Unruhiges oder verwackeltes Videomaterial, störende Vibrationen sowie störende CMOS-Sensor-Verzerrungen (wie der Rolling-Shutter- bzw. Jello- und Wobble-Effekt) gehören zu den häufigsten Problemen bei Aufnahmen von Action-Cams, Drohnen, Camcordern oder Smartphones. *Mercalli* wurde entwickelt, um diese Probleme vollständig und effizient zu lösen.

Anstatt das Bild lediglich simpel zu beschneiden und grob zu skalieren, nutzt *Mercalli* hochkomplexe Bildverarbeitungs-Algorithmen. Die Software analysiert Bewegungsvektoren im Subpixel-Bereich entlang der X-, Y- und Z-Achse (einschließlich Rollen, Nicken und Gieren). Dadurch werden Verwacklungen präzise eliminiert, während der natürliche Charakter einer gewollten Kamerafahrt erhalten bleibt. Darüber hinaus behebt *Mercalli* die durch CMOS-Sensoren verursachten Verzerrungen sowie optische Linsenverkrümmungen vollautomatisch.

---

## Technischer Hintergrund & Metadaten

* **Softwareentwickler:** Holger Burkarth
* **Herausgeber:** proDAD GmbH
* **Plattformen:** Windows, macOS (Plug-ins ab 2017), Linux (SDK für Serverumgebungen)
* **Produktkategorie:** Standalone-Anwendung (SAL), Plug-in-Suite für gängige Schnittsysteme (NLE), Kommandozeilen-Interface (CLI), SDK sowie Spezialeinzellösungen (z. B. NUC-Version für medizinische Anwendungen)

---

## Produktversionen & Evolution im Detail

### Mercalli v1 (2007–2010)

* **Zielgruppe & Fokus:** Professionelle und ambitionierte Filmemacher, die unruhige Aufnahmen nachträglich direkt auf der NLE-Timeline stabilisieren wollen.
* **Hauptmerkmale & Neuerungen:**
* Erste Generation der 3D-Videostabilisierung für Windows-Schnittsysteme (Adobe Premiere, Pinnacle Studio, MAGIX u. a.).
* Einführung der Subpixel-Vektoranalyse zur Korrektur von Erschütterungen auf der X-, Y- und Z-Achse.
* Spätere Ergänzung durch eine vereinfachte *Mercalli Easy*-Variante für schnelle Resultate.



### Mercalli v2 (2011–2013)

* **Zielgruppe & Fokus:** Filmemacher und Videografen mit großem Videomaterialaufkommen und Bedarf an Sensor-Fehlerbehebung.
* **Hauptmerkmale & Neuerungen:**
* Einführung der automatischen **CMOS-Verzerrungskorrektur**, um Jello- und Rolling-Shutter-Effekte zu eliminieren.
* Erstmals als eigenständige Standalone-Software (*Mercalli v2 SAL*, ab 2012) verfügbar.
* Erlaubt den komfortablen Stapelbetrieb (Batch-Processing) mehrerer Videodateien ohne ein primäres Schnittprogramm.



### Mercalli v3 (2014)

* **Zielgruppe & Fokus:** Anwender mit hohen Ansprüchen an Analysegeschwindigkeit und Präzision.
* **Hauptmerkmale & Neuerungen:**
* Signifikante Steigerung der Analysegeschwindigkeit und Stabilisierungspräzision.
* Einführung fortschrittlicher Profil-Optionen zur automatischen Erkennung von Objektiv-Mustern und Linsenverzerrungen.



### Mercalli v4 (2016–2017)

* **Zielgruppe & Fokus:** Action-Cam-Nutzer, Drohnen-Pilotinnen und professionelle Cutter auf Windows und macOS.
* **Hauptmerkmale & Neuerungen:**
* Integration der dedizierten **CMOS-Fixr**-Technologie zur mathematischen Behebung komplexer Sensor-Schwingungen.
* Vollautomatische Profilierung von Action-Cams und Fisheye-Linsen.
* Erweiterte Option zur Korrektur dynamischer Zoom-Grenzbereiche, um den Bildverlust durch das Beschneiden (Crop) auf ein absolutes Minimum zu reduzieren.
* Erstmals Veröffentlichung dedizierter Plug-ins für macOS (Final Cut Pro / Premiere Pro) im Jahr 2017.



### Mercalli v5 (2020)

* **Zielgruppe & Fokus:** NLE-Cutter und Videoproduzenten, die eine sofortige Vorschau ohne lange Analysezeiten benötigen.
* **Hauptmerkmale & Neuerungen:**
* Technologischer Durchbruch mit **Mercalli RT**: Erstmalige Stabilisierung in **Echtzeit** direkt auf der Timeline der Schnittsoftware ohne zeitaufwendige vorherige Analysephase.
* Einführung der Bild- und Farboptimierung (*Mercalli PicEnhancer*) zur automatischen Anpassung von Kontrast, Schärfe und Dynamik.



### Mercalli v6 (2022–2026)

* **Zielgruppe & Fokus:** High-End-Videoproduktionen, TV-Sendeanstalten und Industrie-Anwendungen.
* **Hauptmerkmale & Neuerungen:**
* Einsatz modernster Bildverarbeitungs-Algorithmen mit KI-gestützter Analyse-Unterstützung.
* **Umfassende All-in-One-Optimierung:** Kombiniert Stabilisierung, CMOS-Korrektur und Linsenentzerrung mit fortschrittlicher Farb- und Belichtungskorrektur in einem einzigen Arbeitsgang.
* **Ultraschnelles Rendering:** Optimal angepasst für moderne Mehrkern-Prozessoren und GPU-Beschleunigung.
* **Volle Kontrolle:** Detaillierte Feineinstellung über Weichheit der Kameraführung, Zoom-Verhalten und Kantenbearbeitung.
* Erweiterung des Produktportfolios um *Mercalli CLI* (Kommandozeile) und ein *Linux SDK* für automatisierte Workflows und Serverumgebungen.



---

## Alleinstellungsmerkmale (USPs) im Überblick

1. **Echte 3D-Bewegungsanalyse:** Korrigiert nicht nur einfache horizontale oder vertikale Wackler, sondern berücksichtigt den vollständigen räumlichen Bewegungsvektor (Roll-, Nick- und Gierachsen).
2. **Mathematische CMOS- & Rolling-Shutter-Korrektur:** Befreit Aufnahmen zuverlässig von den typischen Verzerrungen und „Gelee-Effekten“, die beim Einsatz von CMOS-Sensoren bei schnellen Schwenks oder Vibrationen entstehen.
3. **Maximale Auflösungs- und Bildfeld-Erhaltung:** Durch adaptive Zoom-Algorithmen wird der unvermeidliche Beschnitt des Bildes auf das absolut notwendige Minimum begrenzt.
4. **Echtzeit-Fähigkeit (*Mercalli RT*):** Erlaubt die direkte Beurteilung und Korrektur von Material ohne Wartezeit bei der Analyse direkt auf der Timeline.
5. **Nationale und internationale Industriereferenz:** Nahtlose Integration als nativer Standard oder Plug-in in fast allen gängigen NLE-Systemen (Adobe, Grass Valley EDIUS, DaVinci Resolve, MAGIX, Pinnacle etc.).

---

## Zusammenfassung

proDAD *Mercalli* ist seit vielen Jahren die unangefochtene Benchmark für Videostabilisierung und optische Korrektur. Durch die kontinuierliche Innovation – von der ersten 3D-Vektoranalyse über die mathematische CMOS-Entzerrung bis hin zur Echtzeit-Stabilisierung (RT) und KI-gestützten All-in-One-Optimierung – bietet *Mercalli* eine vollständige Werkzeugsuite für perfekten Stand, flüssige Kamerafahrten und makellose Bildqualität.

---

## Links

* [Startseite](README.de-DE.md)
* [Alle Produkte](ProductTimeline.de-DE.md)
* [Mercalli SDK](https://github.com/HolgerBurkarth/MercalliSDK-Preview)
* [Produkt-Handbuch / Manuals](https://github.com/HolgerBurkarth/proDAD-Manuals/blob/main/Mercalli/sal/de/proDAD%20Mercalli.pdf)
* [YouTube Playlist zu Mercalli](https://www.youtube.com/playlist?list=PL2Q9EsYBnfQCM_T8NS9kmOitzfblmtY9_)
* [Produktseite auf proDAD.com](https://www.prodad.com/Video-Stabilisierung-fuer-Profis/Mercalli-SAL-97864.html)
