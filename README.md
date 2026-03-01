# QR Code Generator

A feature-rich, browser-based QR code generator built with HTML5 and vanilla JavaScript — no build tools or server required.

## Features

- **Multiple module shapes** — Square, Dots (circle), Rounded, Diamond, Vertical bars, Horizontal bars
- **Finder pattern styles** — Standard, Rounded, Circular
- **Colors** — Custom foreground and background colors with hex input and live color pickers
- **Gradients** — Linear, Radial, and Diagonal gradients with optional symmetry
- **Image embedding** — Upload any image to centre it inside the QR code (circular or square, with padding); error correction is automatically raised to **H** to ensure reliability
- **Borders / Frames** — None, Simple, Rounded, Double, or Fancy frame with a customizable label
- **Quiet zone & size controls** — Adjustable quiet zone (2–8 modules) and output size (200–1200 px)
- **Export formats** — PNG, JPEG, WebP, and SVG (vector, with embedded images and correct gradient rendering)
- **Copy to clipboard** — One-click copy of the QR image as PNG
- **Reliable QR codes** — Valid every time; uses the [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) library bundled locally (no CDN dependency)
- **Responsive UI** — Two-column desktop layout collapses to single column on mobile

## Usage

Open `index.html` directly in any modern browser. No installation or internet connection required.

```
open index.html
```

## Screenshot

![QR Code Generator feature preview](https://github.com/user-attachments/assets/eec5e019-b1c0-480d-af53-4e630d688731)

## Files

| File | Description |
|------|-------------|
| `index.html` | The complete single-page application (HTML + CSS + JS) |
| `qrcode.js` | Bundled QR code generation library (MIT license, © Kazuhiko Arase) |
