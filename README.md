# Font → PNG / SVG

A lightweight, offline browser tool to convert custom fonts into transparent PNG or SVG images — no installs, no servers, no nonsense.

## Features

- **Load any font** — drag & drop or select `.ttf`, `.otf`, `.woff`, or `.woff2` files
- **Solid color or gradient** — horizontal or vertical, pick your two colors
- **Text outline** — adjustable color and width, renders cleanly on both PNG and SVG
- **Typography controls** — font size, padding, line height, and text alignment
- **Export as PNG** — up to 4x resolution with transparent background
- **Export as SVG** — font embedded as base64, gradient as native `<linearGradient>`, scales infinitely
- **Live preview** — checkerboard background so you always see the transparency

## Usage

1. Download `font-to-png.html`
2. Open it in any modern browser
3. Load your font, type your text, tweak the settings
4. Hit **↓ PNG** or **↓ SVG**

No internet connection required after the page loads (except for loading the UI fonts from Google Fonts on first open).

## Export formats

| Format | Transparency | Gradient | Font embedded | Scalable |
|--------|-------------|----------|---------------|----------|
| PNG    | ✅           | ✅        | —             | ❌        |
| SVG    | ✅           | ✅        | ✅ (base64)   | ✅        |

## Browser support

Works in any Chromium-based browser or Firefox. The `FontFace` API and Canvas 2D API are required.

## License

MIT
