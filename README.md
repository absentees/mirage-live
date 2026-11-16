# Mirage Live

Single-page, zero-dependency prototype web app for real-time on-device vision using [Cactus Compute's Mirage](https://cactuscompute.com/blog/mirage) (21.6 MB 2-bit WASM model).

## Features
- **100% local in-browser inference**: Runs `cactus.wasm` + `mirage.cact` inside a Web Worker; no video frames or images leave the device.
- **Mobile & desktop camera**: Defaults to the rear camera (`facingMode: "environment"`) with camera flip, live continuous recognition, and single-scan or image-upload modes.
- **Visual overlays**: Bounding boxes, polygon segmentation masks, OCR text boxes, confidence threshold slider, and raw JSON output.

> Note: Mobile browsers require HTTPS for `getUserMedia` camera access (e.g., via GitHub Pages).
