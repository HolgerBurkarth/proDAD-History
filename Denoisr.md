<p align="center">
  <img src="https://img.shields.io/badge/EN-English-cccccc?style=for-the-badge" alt="English (current)">
  <a href="Denoisr.de-DE.md"><img src="https://img.shields.io/badge/DE-Deutsch-dd9900?style=for-the-badge" alt="Deutsch"></a>
</p>

# proDAD Denoisr – High-Performance Real-Time Video Denoising

## Introduction

Image noise is one of the most common problems in video processing, especially in recordings under difficult lighting conditions such as night shots, indoors, or when using cameras with high ISO sensitivity. **proDAD Denoisr** was developed specifically for effective video denoising and image optimization. The plug-in solution is suitable for video material ranging from low to high image noise. Thanks to optimized processing algorithms, **Denoisr** works extremely fast and is capable of processing video material up to UHD resolution in real time.

---

## Technical Background & Metadata

* **Software developer:** Holger Burkarth
* **Publisher:** proDAD GmbH
* **Platforms:** Windows, macOS (NLE host systems)
* **Product category:** Video plug-in / noise reduction filter
* **Color space & bit depth:** Processing in the YUV color space with 8-bit and 10-bit color depth

---

## Product Versions & Evolution in Detail

### proDAD Denoisr v1 (2026)

* **Target audience & focus:** Videographers, filmmakers, YouTubers, and editors who want to quickly, flexibly, and with high quality minimize image noise and color flicker in their video recordings.
* **Key features & innovations:**
* **Optimized presets:** Integrated, preconfigured presets for various application scenarios provide a quick start and accelerate the workflow.
* **Spatial Noise Reduction (Spatial Frame Noise):**
* *Luma Frame Noise (Spatial):* Analyzes and smooths luminance noise within a single frame based on neighboring pixels. Ideal for targeted cleaning of luminance noise (e.g., grain in shadow areas) without affecting the color channels.
* *Chroma Frame Noise (Spatial):* Controls spatial noise reduction in the chrominance channel. Removes color noise and color flicker in shadow areas on a frame-by-frame basis.
* **Temporal Noise Reduction (Temporal Motion Noise - TNR):**
* *Luma Motion Noise (Temporal):* Regulates the intensity of time-based noise reduction in the luminance channel. Using statistical analyses, similar areas are compared and averaged across multiple frames, which preserves static details much better than purely spatial filtering.
* *Chroma Motion Noise (Temporal):* Regulates temporal noise reduction in the chrominance channel across multiple consecutive frames.

---

## Unique Selling Points (USPs) at a Glance

1. **Real-time processing up to UHD:** Extremely fast performance that filters and processes even high-resolution UHD video material in real time.
2. **Combined Spatial & Temporal Noise Reduction (TNR):** The separation of spatial (frame-based) and temporal (cross-frame) noise reduction enables maximum sharpness and detail fidelity in moving video material without motion blur.
3. **Separate Luma and Chroma control:** Luminance (brightness) and chrominance (color) noise can be precisely fine-tuned separately to perfectly adjust visual artifacts.
4. **Intuitive preset control:** Predefined settings provide immediate results for typical noise scenarios and serve as a flexible basis for custom fine-tuning.

---

## Summary

**proDAD Denoisr** provides a powerful and user-friendly solution for minimizing image noise in videos. Through the combination of spatial and temporal noise reduction as well as separate control of luma and chroma channels, the software achieves natural, sharp images even in extreme low-light and high-ISO recordings. With real-time processing at UHD resolution, Denoisr integrates seamlessly and saves time in professional post-production workflows.

---

## Links

* [Home](README.md)
* [All Products](ProductTimeline.md)
* [Product Manual / Manuals on GitHub](https://github.com/HolgerBurkarth/proDAD-Manuals/blob/main/Denoisr%20v1/en/proDAD_Denoisr.pdf)