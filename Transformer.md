<p align="center">
  <img src="https://img.shields.io/badge/EN-English-cccccc?style=for-the-badge" alt="English (current)">
  <a href="Transformer.de-DE.md"><img src="https://img.shields.io/badge/DE-Deutsch-dd9900?style=for-the-badge" alt="Deutsch"></a>
</p>

# proDAD Transformer: The Revolution in Color Quantization and Image Conversion

*Transformer* is one of proDAD's outstanding technical pioneering achievements on the Amiga platform. Developed in 1993 as a specialized conversion tool, the software solved one of the most pressing problems of digital image and video processing at the time: the high-quality conversion and reduction of color spaces.

---

## *Transformer* (Amiga, 1993)

* **Software Developer:** Holger Burkarth
* **Manufacturer:** proDAD GmbH
* **Platform:** Exclusively for Amiga
* **Product Category:** High-end image and video sequence converter / quantization tool

### Description & Scope
In the early 1990s, the visual quality of video processing on home computers was severely limited by the hardware restrictions of graphics systems. While image sources such as scanners, TrueColor graphics cards, or high-end rendering programs delivered image data in 24-bit TrueColor (16.7 million colors), standard Amiga systems could often display only limited palettes of 4 to 256 colors simultaneously on the graphics side.

*Transformer* closed this gap as a universal tool for converting single images and complete video sequences. The main focus of development was extremely high visual quality in color quantization. In addition, the software enabled low-loss conversion between various Amiga-specific image and animation formats.

### Technical Innovation & Core: k-Means Color Quantization
The technological core of *Transformer* was a quantization algorithm independently developed by proDAD, which mathematically falls into the category of **k-means cluster analysis**.

#### How did this innovation work?
1. **Intelligent Color Space Analysis:** Instead of reducing colors using rigid tables or simple mathematical grids, the algorithm dynamically analyzed the source material in three-dimensional color space.
2. **Cluster Formation (k-Means):** The algorithm mathematically grouped millions of source colors around optimal centroids (clusters) in such a way that visible deviations for the human eye remained minimal.
3. **Visual Perfection:** As a result, distracting gradation artifacts (banding) and strong image noise, which occurred with conventional dithering methods, were drastically reduced.

For the 1993 release year, this approach represented a small technological revolution in desktop video processing, as it could reproduce TrueColor media on 8-bit and AGA systems with previously unattainable plasticity and color fidelity.

---

## Integration into the proDAD Ecosystem

Due to the outstanding efficiency and image quality of the quantization engine, *Transformer* not only served as a standalone tool but also formed the technological foundation as a core component for other professional proDAD solutions of the Amiga era:

* **Integration into *ClariSSA v3* (1993):** In *ClariSSA v3*, the *Transformer* engine handled high-quality color and format preparation of animation sequences before conversion into the fluid SSA format (*Super-Smooth-Animation*).
* **Integration into *Konrad* (1993):** As an image converter for *Adorage*, *Transformer* provided the necessary color precision to optimally prepare graphics and masks for further processing in *Adorage*.

---

## Main Features & Unique Selling Points at a Glance

* **Top Visual Quality:** Highest color fidelity when reducing colors from 24-bit TrueColor to Amiga-typical palettes (4 to 256 colors).
* **Revolutionary k-Means Algorithm:** Proprietary development for intelligent color clustering in 1993.
* **Comprehensive Format Support:** Conversion between TrueColor formats and all common Amiga graphics and sequence formats.
* **Multimedia Versatility:** Processing of single images as well as complete video sequences.
* **Modular Building Block:** Successful use as a core engine in *ClariSSA v3* and *Konrad*.

---

## Links
- [Home](README.md)
- [All Products](ProductTimeline.md)