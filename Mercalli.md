<p align="center">
  <img src="https://img.shields.io/badge/EN-English-cccccc?style=for-the-badge" alt="English (current)">
  <a href="Mercalli.de-DE.md"><img src="https://img.shields.io/badge/DE-Deutsch-dd9900?style=for-the-badge" alt="German"></a>
</p>

# Mercalli – Industry Standard & Global Reference for Video Stabilization, Lens Distortion Correction, and CMOS Correction

## Introduction

Shaky or blurred video footage, distracting vibrations, and distracting CMOS sensor distortions (such as the rolling shutter, jello, and wobble effects) are among the most common problems when shooting with action cams, drones, camcorders, or smartphones. *Mercalli* was developed to solve these problems completely and efficiently.

Instead of simply cropping the image and roughly scaling it, *Mercalli* uses highly complex image-processing algorithms. The software analyzes motion vectors at subpixel level along the X, Y, and Z axes (including roll, pitch, and yaw). This precisely eliminates shake while preserving the natural character of an intentional camera movement. In addition, *Mercalli* automatically corrects distortions caused by CMOS sensors as well as optical lens distortion.

---

## Technical Background & Metadata

* **Software developer:** Holger Burkarth
* **Publisher:** proDAD GmbH
* **Platforms:** Windows, macOS (plug-ins from 2017), Linux (SDK for server environments)
* **Product category:** Standalone application (SAL), plug-in suite for common editing systems (NLE), command-line interface (CLI), SDK, and custom one-off solutions (e.g., NUC version for medical applications)

---

## Product Versions & Evolution in Detail

### Mercalli v1 (2007–2010)

* **Target audience & focus:** Professional and ambitious filmmakers who want to stabilize shaky footage afterward directly on the NLE timeline.
* **Key features & innovations:**
  * First generation of 3D video stabilization for Windows editing systems (Adobe Premiere, Pinnacle Studio, MAGIX, etc.).
  * Introduction of subpixel vector analysis for correcting shake on the X, Y, and Z axes.
  * Later expanded with a simplified *Mercalli Easy* variant for fast results.

### Mercalli v2 (2011–2013)

* **Target audience & focus:** Filmmakers and videographers with large volumes of video material and a need for sensor error correction.
* **Key features & innovations:**
  * Introduction of automatic **CMOS distortion correction** to eliminate jello and rolling shutter effects.
  * First available as standalone software (*Mercalli v2 SAL*, from 2012).
  * Allows convenient batch processing of multiple video files without a primary editing program.

### Mercalli v3 (2014)

* **Target audience & focus:** Users with high demands on analysis speed and precision.
* **Key features & innovations:**
  * Significant increase in analysis speed and stabilization precision.
  * Introduction of advanced profile options for automatic detection of lens patterns and lens distortion.

### Mercalli v4 (2016–2017)

* **Target audience & focus:** Action cam users, drone pilots, and professional editors on Windows and macOS.
* **Key features & innovations:**
  * Integration of dedicated **CMOS-Fixr** technology for mathematical correction of complex sensor oscillations.
  * Fully automatic profiling of action cams and fisheye lenses.
  * Expanded option for correcting dynamic zoom limits to reduce image loss from cropping to an absolute minimum.
  * First release of dedicated plug-ins for macOS (Final Cut Pro / Premiere Pro) in 2017.

### Mercalli v5 (2020)

* **Target audience & focus:** NLE editors and video producers who need immediate preview without long analysis times.
* **Key features & innovations:**
  * Technological breakthrough with **Mercalli RT**: First-ever stabilization in **real time** directly on the editing software timeline without a time-consuming prior analysis phase.
  * Introduction of image and color optimization (*Mercalli PicEnhancer*) for automatic adjustment of contrast, sharpness, and dynamics.

### Mercalli v6 (2022–2026)

* **Target audience & focus:** High-end video productions, TV broadcasters, and industrial applications.
* **Key features & innovations:**
  * Use of state-of-the-art image-processing algorithms with AI-assisted analysis support.
  * **Comprehensive all-in-one optimization:** Combines stabilization, CMOS correction, and lens distortion correction with advanced color and exposure correction in a single pass.
  * **Ultra-fast rendering:** Optimized for modern multi-core processors and GPU acceleration.
  * **Full control:** Detailed fine-tuning via camera movement smoothness, zoom behavior, and edge handling.
  * Expansion of the product portfolio with *Mercalli CLI* (command line) and a *Linux SDK* for automated workflows and server environments.

---

## Unique Selling Points (USPs) at a Glance

1. **True 3D motion analysis:** Corrects not only simple horizontal or vertical shake but takes the complete spatial motion vector into account (roll, pitch, and yaw axes).
2. **Mathematical CMOS & rolling shutter correction:** Reliably frees footage from the typical distortions and “jello effects” that occur when using CMOS sensors during fast pans or vibrations.
3. **Maximum resolution and field-of-view preservation:** Adaptive zoom algorithms limit the unavoidable cropping of the image to the absolute minimum necessary.
4. **Real-time capability (*Mercalli RT*):** Allows direct assessment and correction of material without waiting for analysis directly on the timeline.
5. **National and international industry reference:** Seamless integration as a native standard or plug-in in almost all common NLE systems (Adobe, Grass Valley EDIUS, DaVinci Resolve, MAGIX, Pinnacle, etc.).

---

## Summary

proDAD *Mercalli* has been the undisputed benchmark for video stabilization and optical correction for many years. Through continuous innovation—from the first 3D vector analysis to mathematical CMOS correction to real-time stabilization (RT) and AI-assisted all-in-one optimization—*Mercalli* offers a complete tool suite for perfect stability, smooth camera movements, and flawless image quality.

---

## Links

* [Home](README.md)
* [All Products](ProductTimeline.md)
* [Mercalli SDK](https://github.com/HolgerBurkarth/MercalliSDK-Preview)
* [Product Manual / Manuals](https://github.com/HolgerBurkarth/proDAD-Manuals/blob/main/Mercalli/sal/en/proDAD%20Mercalli.pdf)
* [YouTube Playlist for Mercalli](https://www.youtube.com/playlist?list=PL2Q9EsYBnfQCM_T8NS9kmOitzfblmtY9_)
* [Product Page on proDAD.com](https://www.prodad.com/Video-Stabilisierung-fuer-Profis/Mercalli-SAL-97864.html)