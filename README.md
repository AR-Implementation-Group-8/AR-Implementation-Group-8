# AR-Implementation-Group-8

A small Hiro-marker AR exhibit built with A-Frame and AR.js for GitHub Pages hosting.

## Pages
- `index.html` — AR experience for the phone
- `marker.html` — Hiro marker page for the laptop screen

## Local setup
1. Open a terminal in this project folder.
2. Run: `python -m http.server 8000`
3. Visit:
   - Laptop: `http://localhost:8000/marker.html`
   - Phone: `http://localhost:8000/index.html`

## Cross-device use
- Open the marker page on the laptop.
- Open the AR page on the phone.
- Hold the laptop screen so the phone camera can see the Hiro marker.
- Allow camera permissions on the phone.

## Model credit
- Model: Boom Box
- Source: KhronosGroup glTF Sample Assets
- Model files: CC0-1.0
- Metadata and documentation: CC-BY-4.0
- Source URL: https://github.com/KhronosGroup/glTF-Sample-Assets/tree/main/Models/BoomBox

## GitHub Pages
This project is designed as a static site, so it can be published directly through GitHub Pages without any build step.
