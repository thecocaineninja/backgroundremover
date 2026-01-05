# Magic Background Remover

A lightweight, privacy-first background remover that runs **100% in your browser** — no uploads, no accounts, no server.

**Live demo:** (add your GitHub Pages / site URL here)

---

## What it does

- Remove backgrounds using:
  - **Brush erase** (manual)
  - **Restore brush** (paint original pixels back)
  - **Magic Wand** (flood-fill by tolerance)
  - **Chroma Key** (pick a color + tolerance)
- **Before / After compare** (press-and-hold or click-to-latch)
- **Undo / Redo / Reset**
- **Preview background presets** (checkerboard, colors, gradients)
- Download:
  - **PNG** (transparent)
  - **WebP** (transparent)
  - **JPEG** (white background)
  - **Mask-only PNG**

---

## Privacy

All processing happens locally in your browser using the Canvas API.

- ✅ No image uploads
- ✅ No accounts
- ✅ No backend required

---

## Getting started

### Option 1: Open it directly
Just open `index.html` in your browser.

> Note: Some browsers restrict certain features when opened as a local file. If anything is weird, use a local server (Option 2).

### Option 2: Run a local server (recommended)

#### Python
```bash
python3 -m http.server 8080
```
Then open:
- `http://localhost:8080`

#### Node
```bash
npx serve .
```

---

## Deploy (static hosting)

This project is plain static files. You can deploy it anywhere:

- GitHub Pages
- Netlify
- Cloudflare Pages
- Any shared hosting / S3 bucket / CDN

### GitHub Pages quick deploy
1. Push to a GitHub repo
2. Go to **Settings → Pages**
3. Source: **Deploy from branch**
4. Branch: `main` / Folder: `/ (root)`

---

## Files

Typical layout:

```
.
├── index.html
├── manifest.json
├── sw.js
├── icon-192.png
├── icon-512.png
├── favicon.ico
└── robots.txt
```

---

## Support

If this tool saved you time:

☕ Buy me a coffee: https://www.buymeacoffee.com/thecocaineninja

---

## License

Apache License 2.0 — see `LICENSE`.
