# proDAD pOS: Das hochmodulare Next-Generation-Betriebssystem

*pOS* (*proDAD Operating System*) gehört zu den mutigsten, ambitioniertesten und technisch beeindruckendsten Großprojekten in der Geschichte von proDAD. Entwickelt zwischen 1995 und 1998 in jahrelanger Einzelarbeit von Holger Burkarth, entstand *pOS* als Antwort auf das drohende Ende der klassischen Amiga-Plattform nach der Insolvenz von Commodore. Ziel war es, den einzigartigen Geist, die Schnelligkeit und die Multitasking-Architektur von AmigaOS in ein völlig neu geschriebenes, modernes, objektorientiertes und hardwareunabhängiges Betriebssystem für die Zukunft zu retten.

---

## *pOS* (1995–1998)

* **Softwareentwicker:** Holger Burkarth
* **Hersteller:** proDAD GmbH
* **Plattform:** Ursprünglich entwickelt auf und für Amiga / konzipiert als hardwareunabhängiges Betriebssystem (PowerPC- und x86-Architekturen)
* **Produktkategorie:** Propriätäres Betriebssystem (Kernel, GUI, Dateisystem & API)

### Beschreibung & Anwendungsbereich
Mitte der 1990er Jahre zeichnete sich der Niedergang der Amiga-Hardware ab. Anstatt sich auf bestehende Systeme wie Microsoft Windows oder veraltete AmigaOS-Strukturen zu beschränken, entwarf proDAD ein eigenes, schlankes Betriebssystem von Grund auf neu. *pOS* sollte Entwicklern und Anwendern eine hochperformante, ausfallsichere und moderne Umgebung bieten, die echtes präemptives Multitasking mit extrem geringen Systemlatenzen vereinte.

### Technische Innovationen & Architektur-Highlights

1. **Echtzeitfähiger, präemptiver Microkernel:**
   * Wichtigstes Herzstück von *pOS* war ein extrem schneller Kernel mit präemptivem Multitasking.
   * Er verfügte über ein hochoptimiertes Nachrichten-basiertes Inter-Process-Communication-System (IPC), eine dynamische Speicherverwaltung sowie ein ausgeklügeltes Prozess-Scheduling.

2. **Objektorientierte C++ Architektur:**
   * *pOS* war eines der ersten Betriebssysteme dieser Klasse, dessen Benutzeroberfläche und Objektverwaltung vollständig modular in C++ strukturiert und programmiert wurden.
   * Sämtliche Systemressourcen, Fenster, Eingabeelemente und Treiber waren als wiederverwendbare Objekte definiert.

3. **Modulares Dateisystem & Abstraktionsschicht:**
   * Das Betriebssystem nutzte eigene Abstraktionsschichten für Hardwaretreiber und Speichermedien.
   * Dies ermöglichte eine vollständige Entkopplung der Software von der zugrundeliegenden Prozessorarchitektur, sodass *pOS* problemlos auf neue Chipsets (wie PowerPC oder PC-Hardware) portiert werden konnte.

4. **Moderne Grafische Benutzeroberfläche (GUI):**
   * Bietet ein objektorientiertes Fenstersystem mit vollem Event-Handling, dynamischem Rendering, konfigurierbaren Themes und intuitiver Bedienung.

---

## Technologischer Hintergrund & Systemhistorie

Obwohl *pOS* in der Fachwelt und bei Entwicklern für seine technologische Eleganz und Performance große Bewunderung auslöste, entschied sich proDAD 1998 schweren Herzens gegen eine kommerzielle Weiterführung. Durch den raschen Wandel des Computermarktes und das Fehlen einer ausreichend breiten Entwickler-Community für Dritthersteller-Software fehlte dem System das nötige Software-Ökosystem.

Dennoch bildete die dreijährige Entwicklungsarbeit an *pOS* das stählerne Fundament für die Zukunft von proDAD: Die dabei perfektionierten C++-Klassenstrukturen, Speicherverwaltungs-Algorithmen und Systemarchitekturen flossen direkt in die Neuentwicklung der proDAD-Werkzeuge für Microsoft Windows ein.

---

## Hauptmerkmale & Alleinstellungsmerkmale auf einen Blick

* **Komplette Eigenentwicklung:** Eigenständiger Kernel, Treiber-Stack und GUI aus einer Hand.
* **Präemptives Multitasking:** Höchste Reaktionsgeschwindigkeit und extrem geringe Latenzen.
* **C++ Objektorientierung:** Saubere, zukunftssichere Modul- und Objektarchitektur.
* **Hardware-Unabhängigkeit:** Konzipiert für den flexiblen Wechsel auf moderne Prozessor-Plattformen.


## Links
- [Startseite](README.de-DE.md)
- [Alle Produkte](ProductTimeline.de-DE.md)
