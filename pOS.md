<p align="center">
  <img src="https://img.shields.io/badge/EN-English-cccccc?style=for-the-badge" alt="English (current)">
  <a href="pOS.de-DE.md"><img src="https://img.shields.io/badge/DE-Deutsch-dd9900?style=for-the-badge" alt="Deutsch"></a>
</p>


# proDAD pOS: The Highly Modular Next-Generation Operating System

*pOS* (*proDAD Operating System*) is one of the boldest, most ambitious, and technically impressive large-scale projects in the history of proDAD. Developed between 1995 and 1998 over years of solo work by Holger Burkarth, *pOS* emerged as a response to the impending end of the classic Amiga platform after Commodore's bankruptcy. The goal was to rescue the unique spirit, speed, and multitasking architecture of AmigaOS into a completely rewritten, modern, object-oriented, and hardware-independent operating system for the future.

---

## *pOS* (1995–1998)

* **Software developer:** Holger Burkarth
* **Manufacturer:** proDAD GmbH
* **Platform:** Originally developed on and for Amiga / designed as a hardware-independent operating system (PowerPC and x86 architectures)
* **Product category:** Proprietary operating system (kernel, GUI, file system & API)

### Description & Scope
In the mid-1990s, the decline of Amiga hardware was becoming apparent. Instead of limiting itself to existing systems such as Microsoft Windows or outdated AmigaOS structures, proDAD designed its own lean operating system from scratch. *pOS* was intended to offer developers and users a high-performance, fail-safe, and modern environment that combined true preemptive multitasking with extremely low system latencies.

### Technical Innovations & Architecture Highlights

1. **Real-Time-Capable, Preemptive Microkernel:**
   * The most important core of *pOS* was an extremely fast kernel with preemptive multitasking.
   * It featured a highly optimized message-based Inter-Process Communication (IPC) system, dynamic memory management, and sophisticated process scheduling.

2. **Object-Oriented C++ Architecture:**
   * *pOS* was one of the first operating systems in its class whose user interface and object management were fully modularly structured and programmed in C++.
   * All system resources, windows, input elements, and drivers were defined as reusable objects.

3. **Modular File System & Abstraction Layer:**
   * The operating system used its own abstraction layers for hardware drivers and storage media.
   * This enabled complete decoupling of the software from the underlying processor architecture, so *pOS* could be easily ported to new chipsets (such as PowerPC or PC hardware).

4. **Modern Graphical User Interface (GUI):**
   * Provides an object-oriented window system with full event handling, dynamic rendering, configurable themes, and intuitive operation.

---

## Technological Background & System History

Although *pOS* inspired great admiration among experts and developers for its technological elegance and performance, in 1998 proDAD reluctantly decided against commercial continuation. Due to the rapid changes in the computer market and the lack of a sufficiently broad developer community for third-party software, the system lacked the necessary software ecosystem.

Nevertheless, the three years of development work on *pOS* formed the steel foundation for proDAD's future: The C++ class structures, memory management algorithms, and system architectures perfected during this work flowed directly into the new development of proDAD tools for Microsoft Windows.

---

## Key Features & Unique Selling Points at a Glance

* **Complete In-House Development:** Independent kernel, driver stack, and GUI from a single source.
* **Preemptive Multitasking:** Highest response speed and extremely low latencies.
* **C++ Object Orientation:** Clean, future-proof module and object architecture.
* **Hardware Independence:** Designed for flexible migration to modern processor platforms.


## Links
- [Home](README.md)
- [All Products](ProductTimeline.md)