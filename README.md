# High-End Editorial Magazine Layout

<p align="center">
  <img width="595" height="842" alt="VOGUE1" src="https://github.com/user-attachments/assets/942dd10e-0972-4352-a0f8-76d4d5827e73" />
</p>

## Overview
A structural recreation of a high-end fashion magazine cover (inspired by Vogue/Elle) designed entirely in Figma. This project demonstrates advanced Z-index layer management, spatial balancing, and professional typographic hierarchy. 

While this is a graphic design exercise, the techniques applied here—specifically layer masking and visual weight distribution—are directly translatable to front-end mobile architecture and complex UI screen design where elements must overlap elegantly.

## Key Design Features
* **The "Sandwich Effect" (Layer Masking):** Achieved depth by duplicating the main subject, removing the top layer's background, and placing the massive masthead (`VOGUE`) *between* the background and the foreground subject.
* **Typographic Hierarchy:** Mixed contrasting font classifications (high-contrast Serif for the masthead, clean Sans-Serif for cover lines) and weights (Bold vs. Light/Thin) to guide the reader's eye and establish priority.
* **Overlapping Depth:** Used razor-thin, oversized typography (`ELEGANCE`) in the absolute foreground, overlapping the subject's clothing to create a premium, multidimensional aesthetic.
* **Micro-Interactions & Realism:** Incorporated authentic editorial details, including mixing italics in single sentences (e.g., "THE YEAR *of*"), precise date anchoring, and an industry-standard EAN-13 barcode.

## Tools & Plugins Used
* **Design Engine:** Figma
* **Background Removal:** Icons8 / Remove BG (for subject masking)
* **Vector Assets:** CODE-128 EAN-13 ITF-14 Barcode Generator (for retail-accurate barcodes)

## Figma Techniques Demonstrated
* **Z-Index Layer Management:** Precise stacking of foreground, midground (text), and background elements.
* **Text Property Manipulation:** Inline font-weight and font-family adjustments within single text nodes.
* **Negative Space Utilization:** Anchoring text blocks in the natural empty pockets of the composition to maintain readability without cluttering the focal point.

## Setup & Viewing
1. View the exported high-resolution `PNG` or `JPG` included in this repository.
2. Notice the interaction between the subject's hair and the background typography, demonstrating the core masking technique.
