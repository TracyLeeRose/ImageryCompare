# ProAlign Suite: Professional Image Registration & Analysis
**By Tracy Rose**

ProAlign is a suite of browser-based tools designed for precise image registration, alignment, and comparison. Whether you are analyzing satellite imagery, comparing historical maps, or performing change detection in medical scans, ProAlign provides a visual, math-driven interface to sync images taken from different angles, rotations, and scales.

---

## 🛠 The Tools

### 1. ProAlign V6 (The Standard Edition)
A streamlined tool for quick alignment of two images. 
- **Best for:** Standard photography, simple TIFF comparisons, and quick overlay checks.
- **Key Feature:** Side-by-side registration and a simple "wipe" slider for comparison.

### 2. ProAlign V9 (The Satellite Edition)
A high-performance version designed for large-scale and multi-spectral data.
- **Best for:** Remote sensing, satellite data (Landsat/Sentinel), and high-resolution change detection.
- **Key Features:** 
    - **Multi-Spectral Composites:** Build images by loading separate Near-Infrared (NIR), Red, and Green bands.
    - **Advanced Zoom Engine:** High-performance zoom-to-cursor and drag-to-pan functionality.
    - **High-Res Handling:** Optimized for professional TIFF files.

---

## ✨ Core Features

- **Point-Based Registration:** Place matching landmarks on both images; the software automatically calculates the translation, rotation, and scaling required to align them.
- **Native TIFF Support:** Built-in decoding for `.tif` and `.tiff` files via `UTIF.js`.
- **Interactive Comparison:** Use a "Wipe" slider to transition between base and overlay images to detect minute differences.
- **Client-Side Processing:** All processing happens in your browser. No images are uploaded to a server, ensuring privacy and speed.

---

## 🚀 How To Use

### Step 1: Load Images
- **V6:** Click "Load Base" and "Load Overlay."
- **V9:** Load specific color bands (NIR, Red, Green) in the sidebar to create a composite image.

### Step 2: Register Landmarks
1. Click **+ Add New Pair**.
2. Drag the crosshair on the **Reference** image (left) to a specific landmark.
3. Drag the matching crosshair on the **Overlay** image (right) to the same landmark.
4. Add at least **2-3 pairs** spread across the image for the best mathematical fit.

### Step 3: Compare
1. Switch to the **Compare** tab.
2. Use the **Slider Bar** to wipe between the two images.
3. **(V9 only):** Use the **Mouse Wheel** to zoom in and **Click+Drag** to pan around high-resolution details.

---

## 💻 Technical Details

- **Language:** HTML5, CSS3, Vanilla JavaScript.
- **Dependencies:** [UTIF.js](https://github.com/photopea/UTIF.js) (via CDN) for TIFF decoding.
- **Math Engine:** Uses Centroid-based registration to calculate Rotation, Scale, and Translation (RST).

### Installation
No installation is required. Simply download the `.html` files and open them in any modern web browser (Chrome, Firefox, Edge, or Safari).

```bash
# Clone the repository
git clone https://github.com/your-username/proalign-suite.git

# Open the version you need
open ProAlign_V9.html
```

---

## ⚖️ License
This project is provided for professional and educational use. 

**Created by Tracy Rose**
*Precision tools for visual discovery.*
