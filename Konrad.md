<p align="center">
  <img src="https://img.shields.io/badge/EN-English-cccccc?style=for-the-badge" alt="English (current)">
  <a href="Konrad.de-DE.md"><img src="https://img.shields.io/badge/DE-Deutsch-dd9900?style=for-the-badge" alt="Deutsch"></a>
</p>

# proDAD Konrad: Specialized Image Conversion for Optimal Adorage Animations

*Konrad* is one of the targeted special-purpose tools from proDAD's Amiga era. Released in 1993, the program was created as a direct interface and preparatory helper tool for the effects suite *Adorage*. *Konrad*'s main task was to universally prepare and convert arbitrary external graphics and image sources so that they could be displayed on Amiga hardware in the highest image quality and seamlessly further processed and animated by *Adorage*.

---

## *Konrad* (Amiga, 1993)

* **Software developer:** Holger Burkarth
* **Manufacturer:** proDAD GmbH
* **Platform:** Exclusive to Amiga
* **Product category:** Specialized image converter / companion tool for *Adorage*

### Description & Scope
To create impressive transitions, masks, and picture-in-picture effects in *Adorage* with your own image material, the graphics used had to be precisely matched to the technical characteristics of the Amiga graphics chipset. However, since source materials often came from widely varying sources (such as scanner files, PC formats, or TrueColor render outputs), color distortion, scaling errors, or performance losses frequently occurred without prior optimization.

*Konrad* solved this challenge by acting as a bridge between external image media and the *Adorage* engine.

### Technical Innovation & Interaction with *Transformer*
The foundation of *Konrad*'s high conversion quality was the integrated **_Transformer_ conversion technology**.

* **Intelligent color quantization:** Using the *Transformer* engine working in the background (based on k-means algorithms), *Konrad* converted high-resolution 24-bit TrueColor images or foreign color palettes with minimal loss into Amiga-specific color representation (4 to 256 colors).
* **Visual optimization for animations:** By avoiding color banding and disruptive artifacts, *Konrad* ensured that the converted graphics could be cleanly animated in *Adorage* as masks or effect overlays, without stutters or pixel errors.

### Thoughtful and Simple Operating Concept
Despite the highly complex conversion mathematics running in the background, *Konrad* stood out with an extremely straightforward and user-friendly operating concept that enabled fast work without a long learning curve:

1. **Load source(s):** Import any image files or image sequences.
2. **Choose format:** Select the target format and target resolution suitable for the respective *Adorage* project.
3. **Optional preview:** Check and inspect the visual conversion result directly on screen in advance.
4. **Save:** Output as a finished Amiga image file for immediate reuse in *Adorage*.

---

## Key Features & Unique Selling Points at a Glance

* **Seamless integration:** Specifically developed as a preparatory conversion tool for *Adorage*.
* **Powered by *Transformer*:** Highest image and color quality when converting TrueColor material to Amiga color spaces (4 to 256 colors).
* **Optimal animation foundation:** Guarantees clean edges and flawless color gradients for later animations and fades.
* **Intuitive workflow:** Four-step, foolproof workflow (Load $\rightarrow$ Select format $\rightarrow$ Preview $\rightarrow$ Save).

## Links
- [Home](README.md)
- [All Products](ProductTimeline.md)
