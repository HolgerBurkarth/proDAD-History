<p align="center">
  <a href="Spherixr.md"><img src="https://img.shields.io/badge/EN-English-dd9900?style=for-the-badge" alt="English"></a>
  <img src="https://img.shields.io/badge/DE-Deutsch-cccccc?style=for-the-badge" alt="Deutsch (aktuell)">
</p>


# Spherixr – Die professionelle Plug-in-Lösung für sphärische 360°- und Panorama-Videokorrektur

## Einleitung

Im Zeitalter immersiver Medien, Virtual-Reality-Inhalten und sphärischen Kamera-Systemen stehen Videoproduzenten vor einer besonderen technischen Herausforderung: Während klassische Objektive und Fisheye-Linsen ein begrenztes Sichtfeld (bis zu 180°) erfassen, zeichnen Spezialkameras und 360°-Systeme die komplette Umgebung auf. Das Ergebnis sind stark verzerrte Kugel- oder Equirectangular-Projektionen, die für die klassische Weiterverarbeitung, das Re-Framing oder die perspektivische Korrektur eine hochspezialisierte Mathematik erfordern.

Mit ***Spherixr*** präsentiert proDAD ein leistungsfähiges Spezial-Plug-in, das die Linsen- und Projektionskorrektur auf Objektive und Bildformate mit einem Sichtfeld von weit über 180° erweitert. Es schließt nahtlos an die klassische Linsenentkrümmung (*DeFishr*) an und bringt die jahrzehntelange Erfahrung von proDAD in der Bildverarbeitung direkt auf die Timelines führender professioneller Videoschnittsysteme.

---

## Technischer Hintergrund & Metadaten

* **Softwareentwickler:** Holger Burkarth
* **Herausgeber:** proDAD GmbH
* **Plattformen:** Windows (PC)
* **Produktkategorie:** Plug-in für professionelle NLE-Schnittsysteme (z. B. via OFX / NLE-Schnittstellen)

---

## Produktversionen & Evolution im Detail

### Spherixr v6 (2026)

* **Zielgruppe & Fokus:** Professionelle Editorinnen und Editoren sowie Videoproduzenten von 360°- und Panorama-Inhalten, Virtual Reality (VR) sowie Spezial-Projektionen, die hochgradig verzerrte Aufnahmen direkt im Schnittprogramm anpassen und re-framen möchten.
* **Hauptmerkmale & Neuerungen:**
* **Sichtfeld-Erweiterung über 180°:** Verarbeitung sphärischer Projektionen, 360°-Kamerasysteme und Speziallinsen, die mehr als eine Halbkugel erfassen (einschließlich Equirectangular- und binokularer Formate).
* **Dynamische Blickrichtungssteuerung:** Stufenlose Ausrichtung der Blickrichtung im 360°-Raum über Breitengrad (*Looking toward Latitude*) und Längengrad (*Looking toward Longitude*).
* **Interaktive Mouse-Steuerung:** Direktes und intuitives Anpassen der Blickrichtung per Mauszeiger im Vorschaufenster.
* **Perspektivisches Re-Framing:** Herausnehmen klassischer flacher Video-Perspektiven (Standard-Bildformate) aus vollen 360°-Aufnahmen inklusive virtueller Schwenks.
* **Mathematische Projektionskontrolle:** Exakte Erfassung von Längen- und Breitengraden (*Longitudes & Latitudes captured*) zur präzisen Berechnung des Kugelmodells.
* **Lage- & Formatkorrektur:** Anpassen von *Display Rotation* und *Display Zoom* zur Korrektur schief montierter Kameras sowie *Pixel Aspect Ratio Adjustment* zum Ausgleich verzerrter Sensor-Seitenverhältnisse.
* **Schematische Analyse- & Feedbackmodi (*Visualization*):**
* *Globe View:* Dreidimensionale Kugel-Darstellung zur Anzeige von Blickrichtung, Ausschnitt und Bildrotation.
* *North Pole View:* Nordpol-Perspektive zur Darstellung des von den Objektiven erfassten Abdeckungsbereichs.
* *Rectangle Grid View:* Visualisierung des Rasters aus Längen- und Breitengraden für präzise mathematische Ausrichtungen.
* **Hochleistungs-Interpolation & Hardwarebeschleunigung:** Interpolationsverfahren wie *Cubic Interpolation* (für maximale Schärfe und Artefaktfreiheit) sowie *Linear* und *Nearest Neighbor* (für schnelle Rechenmodi); native GPU-Beschleunigung zur flüssigen Verarbeitung hochauflösender 4K- und 8K-Videostreams.

---

## Alleinstellungsmerkmale (USPs) im Überblick

1. **Nahtlose NLE-Integration:** Keine Notwendigkeit für externe Zwischenschritte oder Konvertierungen – *Spherixr* arbeitet als reines Plug-in direkt auf der Timeline des bevorzugten Schnittsystems.
2. **Umfassende Abdeckung über 180° hinaus:** Perfekte Lösung für 360°-Panoramen und sphärische Speziallinsen, die weit über die Kapazitäten klassischer Entzerrungswerkzeuge hinausgehen.
3. **Interaktives Re-Framing & Visuelles Feedback:** Intuitive Maus-Steuerung im Vorschaufenster in Kombination mit visuellen Analyseansichten (*Globe View*, *North Pole View*, *Grid View*) für schnelles und exaktes Ausrichten.
4. **Mathematische Projektionskontrolle:** Höchste Präzision bei der Definition von erfassetem Längen-/Breitengrad, Bildrotation, Zoom und Pixelseitenverhältnis.

---

## Zusammenfassung

Mit ***Spherixr*** bietet proDAD ein hochentwickeltes Werkzeug für die moderne Immersive-Video-Produktion. Als reine Plug-in-Lösung konzipiert, bringt es komplexe sphärische Projektions- und Blickrichtungskorrekturen in einen schnellen, intuitiven Workflow direkt auf die Timeline professioneller Videobearbeitungssysteme.

---

## Links

* [Startseite](README.de-DE.md)
* [Alle Produkte](ProductTimeline.de-DE.md)
* [Produkt-Handbuch / Manuals auf GitHub](https://github.com/HolgerBurkarth/proDAD-Manuals)