<p align="center">
  <a href="DeFishr.de-DE.md"><img src="https://img.shields.io/badge/DE-Deutsch-dd9900?style=for-the-badge" alt="Deutsch"></a>
  <img src="https://img.shields.io/badge/EN-English-cccccc?style=for-the-badge" alt="English (current)">
</p>

# DeFishr – The Mathematically Precise Lens Distortion Correction for Action Cam, Drone, and Wide-Angle Footage


## Introduction

Wide-angle and fisheye lenses are indispensable in modern videography – from action cam and drone shots to panoramic videos – for capturing the widest possible field of view. However, filmmakers pay for these extreme angles of view with pronounced geometric curvature: straight lines such as horizons, buildings, or fences appear heavily bowed (barrel distortion).

With ***DeFishr***, proDAD has developed a highly specialized software solution that straightens fisheye-induced curvature fully automatically and without visible loss of sharpness. Instead of simple optical blur filters or fixed distortion filters, ***DeFishr*** relies on an exact mathematical correction process using individual lens profiles that specifically compensate for the physical optical properties of the lens being used.

---

## Technical Background & Metadata

* **Software Developer:** Holger Burkarth
* **Publisher:** proDAD GmbH
* **Platform(s):** Windows (PC)
* **Product Category / Operating Mode:** Standalone (SAL) & NLE plug-in

---

## Product Versions & Evolution in Detail

### ***DeFishr v1 SAL*** (2013)

* **Target Audience & Focus:** Action cam users (e.g., GoPro Hero series), videographers, and aerial photographers requiring correction for wide-angle and fisheye footage.
* **Key Features & Innovations:**
* **Two-Part Suite Architecture:** Consisting of the main application *DeFishr* (for fast rectification of videos and photos) and the measurement tool *DeFishr Calibrator*.
* **DeFishr Calibrator:** Enables calibration of new or unknown lenses. The user films a special calibration pattern (grid target), after which the tool measures the mathematical distortion vectors with pixel precision and generates a tailor-made profile.
* **Profile-Based Correction:** Large integrated library of predefined lens profiles for common action cams and video cameras.
* **Manual Readjustment & Control:** Flexible fine-tuning of zoom, image crop, horizon, and X-/Y-axis offset. Offers options such as "Fit to format" (fitting option) for optimal utilization of image resolution, image rotation, and adjustment of the angle of view.
* **Batch Processing:** Efficient batch processing of multiple video files in a single pass.
* **Real-Time Preview:** Integrated before/after comparison function in side-by-side or split-screen mode.
* **Media Support:** Processes common video and image formats (e.g., MOV, MP4, AVI, WMV, JPG, TIFF).


---

### ***DeFishr v1 MAGIX Deluxe*** (2014)

* **Target Audience & Focus:** Users of MAGIX Video deluxe who want to perform lens corrections directly on the editing timeline.
* **Key Features & Innovations:**
* **Native Plug-in:** Directly integrated into the timeline of MAGIX Video deluxe.
* **Avoidance of External Steps:** Allows applying optical rectification without manual exporting and re-importing via external standalone applications.


---

### ***Spherixr v1*** (2026)

* **Target Audience & Focus:** Professional VR, 180°/360° panorama, and immersive video editors.
* **Key Features & Innovations:**
* **Technological Expansion:** Extends the mathematical rectification foundation of *DeFishr* to spherical video formats from 180° up to full 360° panorama footage (VR and fisheye stereo lenses).
* **Spherical Re-Projection:** Enables converting, realigning, panning, and projecting VR/360° videos into standard flat image formats (panning/reframing) without distortion artifacts.
* **Cross-Platform OFX Integration:** Developed as a flexible NLE plug-in for professional editing environments.


---

### ***DeFishr v1 EDIUS Plugin Variant*** (2027)

* **Target Audience & Focus:** Professional broadcasters and EDIUS users with requirements for maximum timeline performance.
* **Key Features & Innovations:**
* **GPU-Accelerated Engine:** Based on a modernized computation engine with a GPU pipeline for real-time rectification without render wait times.
* **Automated Profile Detection:** Reads lens metadata from video files to further accelerate workflows.
* **Pro Workflow:** Seamless integration into Grass Valley EDIUS.

---

## Unique Selling Points (USPs) at a Glance

1. **Exact Lens Measurement with the *DeFishr Calibrator*:** Unlike generic filter tools, the combination of rectifier and calibrator enables the physically exact measurement of any lens via a grid target.
2. **Mathematical Precision Without Quality Loss:** The optical-mathematical approach avoids unclean interpolation errors, preserves fine image details, and maintains maximum image sharpness all the way to the edges.
3. **Optimized Workflows for Every Application:** Whether as a standalone application with batch processing, as an NLE plug-in, or as a GPU-accelerated real-time timeline integration – *DeFishr* covers all production requirements.


---

## Summary

***DeFishr*** is the ultimate specialized tool for removing unsightly curvature from wide-angle and fisheye footage. From the introduction of the two-part standalone suite ***DeFishr v1 SAL*** (including the innovative calibrator) to NLE integrations, all the way to the 360° expansion ***Spherixr*** (2026) and the real-time variant for EDIUS (2027), proDAD continuously sets standards for mathematically exact lens corrections.

---

## Links

* [Home](README.md)
* [All Products](ProductTimeline.md)
* [Product Manual / Manuals](https://github.com/HolgerBurkarth/proDAD-Manuals/blob/main/Defishr%20v1/en/proDAD_Defishr.pdf)