# QR Code Generator Pro

A small, attractive QR code generator built as a single HTML file. Open `index.html` in your browser to generate and download QR codes with custom colors and sizes.

**Features**

- Simple, single-file app: `index.html` (no build step).
- Customize QR foreground and background colors.
- Choose output size (150–300 px).
- Download generated QR as PNG.
- Press `Enter` in the input to generate quickly.
- Uses `qrcodejs` via CDN.

**How to use**

1. Open the project folder and open `index.html` in your browser. In Windows PowerShell you can run:

```powershell
start .\index.html
```

2. Enter a name or URL in the input field.
3. Optionally set **QR Color**, **Background**, and **Size**.
4. Click **Generate** (or press Enter). The QR will appear below.
5. Click **Download QR** to save it as `qrcode.png`.
6. Click **Reset** to clear the input and remove the QR.

**Files**

- `index.html` — The complete UI and logic (uses `https://cdn.jsdelivr.net/npm/qrcodejs/qrcode.min.js`).
- `README.md` — This documentation.

**Troubleshooting**

- If the download button doesn't work, make sure you have generated a QR (canvas must exist).
- Use a modern browser (Chrome, Edge, Firefox) — some older browsers may not support canvas-toDataURL for downloads.

**Credits & License**

- QR generation powered by `qrcodejs` (kazuhiko arase).
- This repository content is available under the MIT License — feel free to reuse and adapt.

**Next steps / Suggestions**

- Host on GitHub Pages for easy sharing.
- Add a small UI for logo embedding or SVG export.
- Add unit/integration tests and a CI workflow if you plan to extend the app.

If you want, I can commit these changes, add a `LICENSE` file, or prepare a one-click GitHub Pages deployment. What would you like next?
