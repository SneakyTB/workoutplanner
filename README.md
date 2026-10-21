# Lift

A workout tracker for iPhone: planned programs, pick-your-own sessions, set logging with rest timer, food tracking (calories and protein), body metrics, goals and progress. All data is stored on the device (localStorage).

## Files
- `index.html` – the app.
- `au-products.js` – about 68,000 Australian packaged foods with barcodes (Open Food Facts, ODbL licence). Loaded when the Food tab opens.
- `zxing.min.js` – barcode reader (@zxing/library 0.21.3, Apache 2.0). Loaded on the first scan.

Whole foods (about 1,600) come from the Australian Food Composition Database Release 3 (FSANZ) and are built into `index.html`.

## Use it
Open the GitHub Pages URL in Safari on iPhone, tap Share, then Add to Home Screen.

## Host with GitHub Pages
Settings > Pages > Deploy from a branch > main / (root). Keep all three files in the root.
