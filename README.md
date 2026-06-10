# LSD AR Experience

Web AR experience with real-time psychedelic AI filter using BodyPix + TensorFlow.js.

## Features
- Live camera feed
- BodyPix AI segmentation (body vs background)
- LSD-style psychedelic effects: hue shifting, channel aberration, liquid rainbow, pixelation, solarization
- Record & download video (WebM)
- Intensity slider
- Fallback mode if AI doesn't load

## Usage
Open `index.html` in Chrome/Firefox or visit the GitHub Pages URL.

## Deploy to GitHub Pages
```
git init
git add .
git commit -m "initial"
git branch -M main
git remote add origin https://github.com/YOUR_USER/ar-lsd-experience.git
git push -u origin main
```
Then enable Pages in repo Settings → Pages → Source: main branch / root.
