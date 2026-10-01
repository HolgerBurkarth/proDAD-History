<p align="center">
  <a href="Denoisr.md"><img src="https://img.shields.io/badge/EN-English-dd9900?style=for-the-badge" alt="English"></a>
  <img src="https://img.shields.io/badge/DE-Deutsch-cccccc?style=for-the-badge" alt="Deutsch (aktuell)">
</p>

# proDAD Denoisr – Hochleistungs-Videorentrauschung in Echtzeit

## Einleitung

Bildrauschen ist eines der häufigsten Probleme in der Videoverarbeitung, insbesondere bei Aufnahmen unter schwierigen Lichtverhältnissen wie Nachtaufnahmen, Innenräumen oder bei Verwendung von Kameras mit hoher ISO-Empfindlichkeit. **proDAD Denoisr** wurde speziell für die effektive Videorentrauschung und Bildoptimierung entwickelt. Die Plug-in-Lösung eignet sich für Videomaterial von geringem bis hohem Bildrauschen. Dank optimierter Verarbeitungsalgorithmen arbeitet **Denoisr** extrem schnell und ist in der Lage, Videomaterial bis hin zu UHD-Auflösung in Echtzeit zu verarbeiten.

---

## Technischer Hintergrund & Metadaten

* **Softwareentwickler:** Holger Burkarth
* **Herausgeber:** proDAD GmbH
* **Plattformen:** Windows, macOS (NLE-Host-Systeme)
* **Produktkategorie:** Video-Plug-in / Filter zur Rauschreduzierung
* **Farbraum & Farbtiefe:** Verarbeitung im YUV-Farbraum mit 8-Bit und 10-Bit Farbtiefe

---

## Produktversionen & Evolution im Detail

### proDAD Denoisr v1 (2026)

* **Zielgruppe & Fokus:** Videografen, Filmemacher, YouTuber und Editoren, die Bildrauschen und Farbflackern in ihren Videoaufnahmen schnell, flexibel und in hoher Qualität minimieren möchten.
* **Hauptmerkmale & Neuerungen:**
* **Optimierte Voreinstellungen (Presets):** Integrierte, vorkonfigurierte Presets für verschiedene Anwendungs-Szenarien bieten einen schnellen Einstieg und beschleunigen den Workflow.
* **Räumliche Rauschreduzierung (Spatial Frame Noise):**
* *Luma Frame Noise (Spatial):* Analysiert und glättet das Helligkeitsrauschen (Luminanz) innerhalb eines einzelnen Einzelbildes basierend auf benachbarten Pixeln. Ideal zum gezielten Säubern von Helligkeitsrauschen (z. B. Körnung in Schattenbereichen), ohne die Farbkanäle zu beeinflussen.
* *Chroma Frame Noise (Spatial):* Steuert die räumliche Rauschreduzierung im Farbkennungskanal (Chrominanz). Entfernt Farbrauschen und Farbflackern in Schattenbereichen bildweise.
* **Temporale Rauschreduzierung (Temporal Motion Noise - TNR):**
* *Luma Motion Noise (Temporal):* Reguliert die Intensität der Zeit-basierten Rauschreduzierung im Luminanzkanal. Mithilfe statistischer Analysen werden ähnliche Bereiche über mehrere Frames hinweg verglichen und gemittelt, wodurch statische Details deutlich besser erhalten bleiben als bei rein räumlicher Filterung.
* *Chroma Motion Noise (Temporal):* Reguliert die temporale Rauschreduzierung im Chrominanzkanal über mehrere aufeinanderfolgende Frames hinweg.


---

## Alleinstellungsmerkmale (USPs) im Überblick

1. **Echtzeitverarbeitung bis UHD:** Extrem schnelle Performanz, die selbst hochauflösendes UHD-Videomaterial in Echtzeit filtert und verarbeitet.
2. **Kombinierte Spatial & Temporal Noise Reduction (TNR):** Die Trennung von räumlicher (Frame-basierter) und zeitlicher (Frame-übergreifender) Rauschunterdrückung ermöglicht maximale Schärfe und Detailtreue bei bewegtem Videomaterial ohne Bewegungsunschärfe.
3. **Getrennte Luma- und Chroma-Kontrolle:** Luminanz- (Helligkeits-) und Chrominanz- (Farb-) Rauschen können getrennt voneinander präzise feinjustiert werden, um visuelle Artefakte perfekt abzustimmen.
4. **Intuitive Preset-Steuerung:** Vordefinierte Einstellungen bieten sofortige Ergebnisse für typische Rauschszenarien und dienen als flexible Basis für eigene Feineinstellungen.

---

## Zusammenfassung

**proDAD Denoisr** liefert eine leistungsstarke und benutzerfreundliche Lösung zur Minimierung von Bildrauschen in Videos. Durch die Kombination aus räumlicher und temporaler Rauschreduzierung sowie der separaten Steuerung von Luma- und Chroma-Kanälen erzielt die Software natürliche, scharfe Bilder selbst bei extremen Low-Light- und High-ISO-Aufnahmen. Mit der Echtzeitverarbeitung in UHD-Auflösung fügt sich Denoisr nahtlos und zeitsparend in professionelle Postproduktions-Workflows ein.

---

## Links

* [Startseite](README.de-DE.md)
* [Alle Produkte](ProductTimeline.de-DE.md)
* [Produkt-Handbuch / Manuals auf GitHub](https://github.com/HolgerBurkarth/proDAD-Manuals/blob/main/Denoisr%20v1/de/proDAD_Denoisr.pdf)
