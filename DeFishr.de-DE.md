<p align="center">
  <a href="DeFishr.md"><img src="https://img.shields.io/badge/EN-English-dd9900?style=for-the-badge" alt="English"></a>
  <img src="https://img.shields.io/badge/DE-Deutsch-cccccc?style=for-the-badge" alt="Deutsch (aktuell)">
</p>

# DeFishr – Die mathematisch präzise Linsenentzerrung für Action-Cam-, Drohnen- und Weitwinkelaufnahmen


## Einleitung

Weitwinkel- und Fischaugenobjektive sind in der modernen Videografie – von Action-Cam- und Drohnenaufnahmen bis hin zu Panoramavideos – unverzichtbar, um ein möglichst breites Sichtfeld einzufangen. Diese extremen Blickwinkel erkaufen sich Filmemacher jedoch mit einer ausgeprägten geometrischen Krümmung: Gerade Linien wie Horizonte, Gebäude oder Zäune wirken stark durchgebogen (Tonnenverzerrung).

Mit ***DeFishr*** hat proDAD eine hochspezialisierte Softwarelösung entwickelt, die fisheye-bedingte Wölbungen vollautomatisch und ohne sichtbare Schärfeverluste begradigt. Statt einfacher optischer Unschärfefilter oder fixer Zerrfilter setzt ***DeFishr*** auf ein exaktes mathematisches Korrekturverfahren über individuelle Linsenprofile, das die physikalischen optischen Eigenschaften des verwendeten Objektivs gezielt ausgleicht.

---

## Technischer Hintergrund & Metadaten

* **Softwareentwickler:** Holger Burkarth
* **Herausgeber:** proDAD GmbH
* **Plattform(en):** Windows (PC)
* **Produktkategorie / Betriebsart:** Standalone (SAL) & NLE-Plug-in

---

## Produktversionen & Evolution im Detail

### ***DeFishr v1 SAL*** (2013)

* **Zielgruppe & Fokus:** Action-Cam-Nutzer (z. B. GoPro Hero-Serie), Videografen und Luftbildfotografen mit Korrekturbedarf für Weitwinkel- und Fischaugenaufnahmen.
* **Hauptmerkmale & Neuerungen:**
* **Zweiteilige Suite-Architektur:** Bestehend aus der Hauptanwendung *DeFishr* (zur schnellen Entzerrung von Videos und Fotos) und dem Mess-Werkzeug *DeFishr Calibrator*.
* **DeFishr Calibrator:** Ermöglicht die Kalibrierung neuer oder unbekannter Linsen. Der Anwender filmt ein spezielles Kalibriermuster (Grid Target), woraufhin das Tool die mathematischen Verzerrungsvektoren pixelgenau vermisst und ein maßgeschneidertes Profil generiert.
* **Profilbasierte Korrektur:** Große integrierte Bibliothek vordefinierter Linsenprofile für gängige Action-Cams und Videokameras.
* **Manuelle Nachjustierung & Steuerung:** Flexibles Feintuning von Zoom, Bildausschnitt, Horizont sowie X-/Y-Achsenverschiebung. Bietet Optionen wie „An Passform ausrichten“ (Fitting option) zur optimalen Ausnutzung der Bildauflösung, Bilddrehung sowie Justierung des Blickwinkels.
* **Batch-Processing:** Effiziente Stapelverarbeitung mehrerer Videodateien in einem Durchgang.
* **Echtzeit-Vorschau:** Integrierte Vorher/Nachher-Vergleichsfunktion im Side-by-Side- oder Split-Screen-Modus.
* **Medienunterstützung:** Verarbeitet gängige Video- und Bildformate (z. B. MOV, MP4, AVI, WMV, JPG, TIFF).


---

### ***DeFishr v1 MAGIX Deluxe*** (2014)

* **Zielgruppe & Fokus:** Anwender von MAGIX Video deluxe, die Linsenkorrekturen direkt auf der Schnitt-Timeline durchführen möchten.
* **Hauptmerkmale & Neuerungen:**
* **Natives Plug-in:** Direkt in die Timeline von MAGIX Video deluxe integriert.
* **Vermeidung externer Schritte:** Erlaubt das Anwenden der optischen Entzerrung ohne manuelles Exportieren und Re-Importieren über externe Standalone-Anwendungen.


---

### ***Spherixr v1*** (2026)

* **Zielgruppe & Fokus:** Professional VR-, 180°/360°-Panorama- und Immersive-Video-Editoren.
* **Hauptmerkmale & Neuerungen:**
* **Technologische Erweiterung:** Weitet das mathematische Entzerrungsfundament von *DeFishr* auf sphärische Videoformate von 180° bis hin zu vollen 360°-Panoramaaufnahmen (VR- und Fisheye-Stereo-Linsen) aus.
* **Sphärische Re-Projection:** Ermöglicht Umwandeln, Neuausrichten, Schwenken und Projizieren von VR-/360°-Videos in Standard-Flachbildformate (Panning/Reframing) ohne Verzerrungsartefakte.
* **Cross-Platform OFX-Integration:** Entwickelt als flexibles NLE-Plugin für professionelle Bearbeitungsumgebungen.


---

### ***DeFishr v1 EDIUS Plugin-Variante*** (2027)

* **Zielgruppe & Fokus:** Professionelle Broadcaster und EDIUS-Anwender mit Anforderungen an maximale Timeline-Performance.
* **Hauptmerkmale & Neuerungen:**
* **GPU-Accelerated Engine:** Basiert auf einer modernisierten Berechnungs-Engine mit GPU-Pipeline für Entzerrung in Echtzeit ohne Renderwartezeiten.
* **Automatisierte Profilerkennung:** Liest Linsenmetadaten aus den Videodateien aus, um Arbeitsabläufe weiter zu beschleunigen.
* **Profi-Workflow:** Nahtlose Integration in Grass Valley EDIUS.

---

## Alleinstellungsmerkmale (USPs) im Überblick

1. **Exakte Linsenvermessung mit dem *DeFishr Calibrator*:** Im Gegensatz zu generischen Filterwerkzeugen ermöglicht die Kombination aus Entzerrer und Kalibrator die physikalisch exakte Ausmessung jedes beliebigen Objektivs über ein Grid-Target.
2. **Mathematische Präzision ohne Qualitätsverlust:** Der optisch-mathematische Ansatz vermeidet unsaubere Interpolationsfehler, schont feine Bilddetails und bewahrt maximale Bildschärfe bis an die Ränder.
3. **Optimierte Workflows für jeden Einsatzbereich:** Ob als eigenständige Standalone-Anwendung mit Stapelverarbeitung, als NLE-Plugin oder als GPU-beschleunigte Echtzeit-Timeline-Integration – *DeFishr* deckt sämtliche Produktionsanforderungen ab.


---

## Zusammenfassung

***DeFishr*** ist das ultimative Spezialwerkzeug, um unschöne Krümmungen aus Weitwinkel- und Fischaugenaufnahmen zu entfernen. Von der Einführung der zweiteiligen Standalone-Suite ***DeFishr v1 SAL*** (inklusive des innovativen Kalibrators) über NLE-Einbindungen bis hin zur 360°-Erweiterung ***Spherixr*** (2026) und der Realtime-Variante für EDIUS (2027) setzt proDAD kontinuierlich Maße für mathematisch exakte Linsenkorrekturen.

---

## Links

* [Startseite](README.de-DE.md)
* [Alle Produkte](ProductTimeline.de-DE.md)
* [Produkt-Handbuch / Manuals](https://github.com/HolgerBurkarth/proDAD-Manuals/blob/main/Defishr%20v1/de/proDAD_Defishr.pdf)