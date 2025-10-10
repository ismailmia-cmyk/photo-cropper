# Passport Photo Cropper

**Passport Photo Cropper** is a lightweight, browser-based image cropper that allows users to upload, crop, and automatically format passport photos for **UK** and **US** standards.  
It supports manual selection with locked aspect ratios, draggable/resizable crop areas, and instant downloads in **JPEG or PNG** formats.

---

## Features

- **Upload any image** and preview instantly  
- **Manual cropping** with locked aspect ratios:
- UK Passport → 7:9 ratio, outputs **413×531 px**
- US Passport → 1:1 ratio, outputs **600×600 px**
- **Resizable, draggable selection box** (Photoshop-style handles)
- **Automatic download** of cropped image (JPEG or PNG toggle)
- **Real-time overlay preview** (see exactly what you crop)
- **No backend required** — runs fully client-side in any modern browser

---

## Installation

No installation needed — simply open the HTML file in your browser.

### Option 1 — Local file
1. Download or clone this repository.  
2. Open `index.html` in your browser.

### Option 2 — Local web server (optional)
Run this in your project directory:
```bash
python -m http.server 8080
