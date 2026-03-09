# VELOX — GPS Speedometer v2

Real-time GPS speedometer PWA. 8 o'clock to 4 o'clock arc. Color-coded speed zones.

## Features
- 240° arc gauge (8 o'clock → 4 o'clock)
- Color-coded: green / orange / red zones + needle
- KM/H, MPH, M/S toggle
- Max speed, average speed, heading, altitude
- GPS signal strength bar
- Wake Lock (screen stays on while tracking)
- PWA installable (offline support)
- Fully self-contained — no external dependencies except Google Fonts

## Deploy

### GitHub Pages (recommended)
1. Push this folder to a GitHub repo
2. Settings → Pages → Branch: main → Save
3. Paste URL into pwabuilder.com for APK

### Netlify Drop
Drag the folder to netlify.com/drop

### Local
Open index.html directly in Chrome (GPS needs HTTPS or localhost)

## Files
| File | Purpose |
|------|---------|
| `index.html` | Complete app (self-contained, works standalone) |
| `manifest.json` | PWA manifest for file-based hosting |
| `sw.js` | Service worker for file-based hosting |
| `icon-192.png` | App icon |
| `icon-512.png` | App icon large |
| `netlify.toml` | Netlify config |
| `vercel.json` | Vercel config |
