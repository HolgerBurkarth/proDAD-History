<p align="center">
  <a href="Vitascene.md"><img src="https://img.shields.io/badge/EN-English-dd9900?style=for-the-badge" alt="English"></a>
  <img src="https://img.shields.io/badge/DE-Deutsch-cccccc?style=for-the-badge" alt="Deutsch (aktuell)">
</p>

# Vitascene – High-End Effekte, Lichtfilter und Transitionen in Echtzeit

## Einleitung

In der professionellen Videobearbeitung, Postproduktion und im Broadcasting erfordern visuelle Effekte und hochwertige Szenenübergänge oft enorme Rechenleistung. Traditionelle Effektberechnungen führen bei hochauflösendem Quellmaterial häufig zu langen Render-Wartezeiten, was den kreativen Workflow erheblich ausbremst.

*Vitascene* von proDAD löst diese Herausforderung durch den konsequenten Einsatz einer hochperformanten, rein GPU-beschleunigten Render-Engine. Anstatt Zeit mit der Vorberechnung aufzuwenden, können Filmemacher und Editorinnen aus einer umfangreichen Bibliothek von hochauflösenden Übergangseffekten, cineastischen Licht- und Farbfiltern, Tilt-Shift-Transformationen sowie modernen Seamless- und Glitch-Transitionen wählen und diese in echter Echtzeit direkt auf der Schnitt-Timeline anwenden, feinfühlig anpassen und sofort in voller Auflösung evaluieren.

---

## Technischer Hintergrund & Metadaten

* **Softwareentwickler:** Holger Burkarth
* **Herausgeber:** proDAD GmbH
* **Plattformen:** Windows (historische Vorläufer-Technologien auf Amiga)
* **Produktkategorie:** Standalone (SAL) & Plug-in (unter anderem Adobe Premiere Pro, Grass Valley EDIUS, MAGIX Video Pro X / Deluxe, Blackmagic DaVinci Resolve via OFX, Corel VideoStudio, Pinnacle Studio, Sony/Magix Vegas)


---

## Produktversionen & Evolution im Detail

### Vitascene v1 (2006)

* **Zielgruppe & Fokus:** Broadcast-Spezialisten, Filmemacher und ambitionierte Videoschneider, die Echtzeit-Effekte ohne lange Renderzeiten suchten.
* **Hauptmerkmale & Neuerungen:**
* Pionierarbeit im Bereich rein Hardware-beschleunigter Effekte via Grafikkarte (GPU-Rendering).
* Bereitstellung als eigenständige Anwendung (*Standalone*) sowie als nahtloses Plug-in für NLEs wie *Pinnacle Studio*, *MAGIX Deluxe*, *EDIUS* und *Avid Studio*.
* Mathematisch präzise berechnete Lichtstrahlen-Effekte (*Ray-Effects*), Glow-Filter, Weichzeichnung und stimmungsaufhellende Farbkorrekturen.



### Vitascene v2 (2013)

* **Zielgruppe & Fokus:** Professionelle Editor-Umgebungen mit Anforderung an hohe Systemstabilität und 64-Bit-NLE-Integration.
* **Hauptmerkmale & Neuerungen:**
* Aufbohrung der Engine auf eine voll native 64-Bit-Architektur für gesteigerte Stabilität und Verarbeitungsgeschwindigkeit in NLEs wie *Adobe Premiere Pro* oder *Sony Vegas*.
* Massiver Ausbau der Vorlagenbibliothek auf über 600 anpassbare Filter und Transitionen.
* Einführung verbesserter Miniatur-Effekte (*Tilt-Shift*), Rahmeneffekte sowie hochwertiger Mosaik- und Verfremdungsfilter.



### Vitascene v3 (2017)

* **Zielgruppe & Fokus:** High-End 4K-Postproduktion und Anwender, die feinfühlige Farb-Gradings und kinoreife Beleuchtungsakzente benötigen.
* **Hauptmerkmale & Neuerungen:**
* Überarbeitete, modernisierte Benutzeroberfläche mit optimierter Multi-GPU- und Multithreading-Unterstützung für flüssiges Bearbeiten von 4K-Material.
* Erweiterung des Katalogpakets auf über 700 Vorlagen.
* Spezialisierte Werkzeuge für kinoreifes Farb-Grading, Blendenflecke (*Lens Flares*) und kontrastfeine Lichtanpassungen.



### Vitascene v4 (2020)

* **Zielgruppe & Fokus:** Content Creator und Video-Editoren, die dynamische, moderne Schnitt-Trends und schnelle Navigationsmöglichkeiten verlangen.
* **Hauptmerkmale & Neuerungen:**
* Integration von *Seamless Transitions* (nahtlose Übergänge durch dynamische Bewegungsunschärfe, Rotations-, Zoom- und Wisch-Effekte).
* Anwachsen des Effektkontingents auf über 1.400 Vorlagen.
* Implementierung eines effizienten Tagging- und Suchsystems innerhalb der Benutzeroberfläche zur raschen Effektfindung.



### Vitascene v5 & v6 OFX (2022)

* **Zielgruppe & Fokus:** Broadcaster, Postproduktionshäuser und Coloristen mit Bedarf an 8K-Performance, Glitch-Ästhetik und plattformübergreifender OFX-Kompatibilität.
* **Hauptmerkmale & Neuerungen:**
* Über 1.700 Vorlagen inklusive moderner Trends wie *Glitch-Effekte* (digitale Bildstörungen), Cyberpunk-Farbverschiebungen und *Light Leaks*.
* Vollständig optimierte Render-Kernel für Auflösungen von SD und HD über 4K bis hin zu 8K-Broadcast-Formaten.
* Bereitstellung der *Vitascene v6 OFX*-Schnittstelle für den universellen Einsatz in OpenFX-Plattformen wie *Blackmagic DaVinci Resolve*.

---

## Alleinstellungsmerkmale (USPs) im Überblick

1. **Konsequente GPU-Echtzeit-Performance:** Durch die direkte Berechnungsarchitektur auf Grafikkarten-Prozessoren entfallen lange Pre-Rendering-Zeiten. Selbst bei hochauflösendem Quellmaterial in 4K oder 8K bleiben Effekte direkt auf der Timeline abspielbar und in Echtzeit editierbar.
2. **Mathematisch exakte Licht- & Partikelberechnung:** Lichtstrahlen, Funken, Glitzereffekte und *Lens Flares* werden dynamisch auf Basis der tatsächlichen Helligkeits- und Farbwerte des zugrundeliegenden Videobilds berechnet, anstatt lediglich als statische Grafik-Overlays abgelegt zu werden.
3. **Flexible Hybrid-Architektur:** Lauffähig als eigenständige Standalone-Anwendung (*SAL*) sowie als nahtlos integrierbares Plug-in (inklusive OFX-Standard) für nahezu alle marktrelevanten Schnittsysteme.
4. **Riesige Vorlagenvielfalt & Skalierbarkeit:** Von klassischen Licht- und Farbfiltern bis hin zu komplexen *Seamless-* und *Glitch-Transitionen* bietet die Suite über 1.700 universell anpassbare Vorlagen.


---

## Zusammenfassung

*Vitascene* etabliert sich seit 2006 als technologischer Maßstab für hochperformante Videoschnitt-Effekte. Durch die Kombination aus exakter mathematischer Lichtberechnung, einer kontinuierlich auf 8K-Auflösungen skalierten GPU-Render-Engine und universeller Plug-in- bzw. OFX-Einbindung ermöglicht die Software Profis wie Einsteigern cineastische visuellen Ergebnisse ohne zeitraubende Render-Unterbrechungen.

---

## Links

* [Startseite](README.de-DE.md)
* [Alle Produkte](ProductTimeline.de-DE.md)
* [Produkt-Handbuch / Manuals (GitHub)](https://github.com/HolgerBurkarth/proDAD-Manuals/blob/main/Vitascene%20v2-v6/de/vitascene-help.pdf)
* [Offizielle Vitascene Produktseite](https://www.prodad.com/Videoeffekte-Uebergaenge/VitaScene-V5-PRO-103685,l-de.html)
* [Vitascene YouTube Playlist](https://www.youtube.com/playlist?list=PLstKIRcOnFakvaU2p-8SK4jc2ozHe3ynr)