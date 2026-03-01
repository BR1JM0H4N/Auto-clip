# Auto-clip

A beautiful single-page HTML app to remove a selected color from an image and export the result as a transparent PNG.

## Features
- Upload an image from your device.
- Pick the color to remove with a color picker.
- Click directly on the image to sample a color (eyedrop behavior).
- Adjust a threshold slider to control color fuzziness.
- Download the processed output as a PNG with transparency.

## Run locally
Because this app is fully client-side, you can open `index.html` directly in a browser.

Or serve it with a local static server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.
