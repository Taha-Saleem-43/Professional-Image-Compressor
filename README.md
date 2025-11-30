# Professional Image Compressor

A modern web-based image compressor that allows you to **optimize JPEG, PNG, and WebP images** directly in your browser. Supports multiple image uploads, adjustable compression quality, and ZIP downloads for batch compression.

---

## 📌 Features

- Drag & drop or browse to select images.
- Supports **JPEG, PNG, and WebP** formats.
- Adjust **compression quality** with a slider (20%–100%).
- Preview compressed images and compare sizes.
- Display **compression stats**:
  - Total original size
  - Total compressed size
  - Space saved
  - Quality used
- Download compressed images individually or as a ZIP file.
- Fully client-side, no server needed.
- Responsive and visually modern UI.

---

## 🛠 Technology Stack

- **HTML5 & CSS3** – layout and styling
- **Vanilla JavaScript** – functionality and compression logic
- **JSZip** – generating ZIP files for multiple images
- 
---

## ▶️ How to Use

1. Open `index.html` in a browser.
2. Drag & drop images into the **upload area**, or click it to browse files.
3. Adjust the **compression quality slider**.
4. Click **"Compress Images"**.
5. Preview the compressed images and see size stats.
6. Click **"Download Compressed Images"** to save:
   - Single image → downloads as `filename_compressed.jpg`
   - Multiple images → downloads as `compressed_images.zip`

## ⚙️ Notes

- Compression is **done client-side**, so no images leave your computer.
- For best results, use modern browsers like Chrome, Firefox, or Edge.
- Large images may take a few seconds to compress depending on your machine.

---

## 📂 Project Structure

