AR-Implementation-Group-8

A small Hiro-marker AR exhibit built with A-Frame and AR.js for GitHub Pages hosting.

Project pages:
- index.html is the phone AR experience.
- marker.html is the laptop view that shows the Hiro marker.

Local setup:
1. Open a terminal in this project folder.
2. Run: python -m http.server 8000
3. Open these pages in a browser:
   - Laptop: http://localhost:8000/marker.html
   - Phone: http://localhost:8000/index.html

Cross-device use:
1. Open the marker page on the laptop.
2. Open the AR page on the phone.
3. Hold the laptop screen so the phone camera can see the Hiro marker.
4. Allow camera permissions on the phone.

Model credit:
Model: Ship in a Bottle
Source: GitHub asset repository sh3h96/furniture-ar-models
File: ship_in_a_bottle.glb
Source URL: https://github.com/sh3h96/furniture-ar-models/blob/main/ship_in_a_bottle.glb
Note: The upstream repository does not include a visible license file, so this project keeps attribution to the original source and uses the model for this non-commercial exhibit only.

GitHub Pages:
This project is a static website, so it can be published directly through GitHub Pages without any build step.
