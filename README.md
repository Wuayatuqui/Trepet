# TreePet PWA

## Option A — Single File (easiest)
Just open `treepet.html` in any browser. Everything is embedded.

## Option B — Deploy to a server (full PWA install)
Upload all files to any static host (GitHub Pages, Netlify, Vercel, etc.):
```
treepet.html
manifest.json
sw.js
icons/
  icon-72.png ... icon-512.png
```
Then open the URL on your phone → browser will offer "Add to Home Screen".

## PWA Features
- ✅ Installable (Add to Home Screen)
- ✅ Works offline (Service Worker cache)
- ✅ Splash screen + theme color
- ✅ Standalone fullscreen (no browser UI)
- ✅ iOS Safari + Android Chrome support
