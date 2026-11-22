MONAVEST — ANDROID + IPHONE INSTALLABLE PWA

IMPORTANT: Deploy the CONTENTS of this folder as the Vercel project root.
Do not deploy the parent folder as a nested directory.

Vercel settings:
- Framework Preset: Other
- Build Command: leave blank
- Output Directory: .
- Install Command: leave blank

Required root files:
- index.html
- manifest.json
- sw.js
- icons/ (four PNG icons)
- assets/ (Google and Apple logo images)

After deployment:
1. Open https://YOUR-DOMAIN/manifest.json. It should display JSON, not a 404 page.
2. Open https://YOUR-DOMAIN/sw.js. It should display JavaScript, not a 404 page.
3. Open https://YOUR-DOMAIN/icons/icon-192.png and icon-512.png. Both should load.
4. On Android, open the HTTPS site in Chrome, reload once, then use the Install Monavest button or Chrome menu > Install app.
5. On iPhone, open the HTTPS site in Safari > Share > Add to Home Screen > Add.

If an older Monavest service worker is already installed, open the site in Chrome,
clear the site's storage/cache once, close the tab, reopen the site, and try again.

PWA limitations:
- Android native installation is offered by supported browsers when PWA checks pass.
- iOS does not expose a website-triggered native install prompt; Safari's Add to Home Screen is required.
- This app stores its demo data locally. It is not a real bank and does not send real payments.
- Tailwind CDN styling requires internet access.
