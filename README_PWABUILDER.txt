MTC Attendance Register - Netlify PWA

This version includes:
- public/index.html
- public/manifest.json
- public/sw.js
- netlify.toml

Deploy the project to Netlify with publish directory: public.
After deployment, open the HTTPS site and run PWABuilder again.

Important:
PWABuilder may still request app icons. If it does, add 192x192 and 512x512 PNG icons
and reference them in manifest.json. The current manifest is valid but intentionally does
not invent an icon image.
