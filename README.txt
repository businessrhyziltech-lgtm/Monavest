MONAVEST — INSTALLABLE PHONE APP (PWA)

DEPLOYMENT
1. Upload/deploy the contents of this folder as the website project root.
2. Keep index.html, manifest.webmanifest and sw.js in the same root folder.
3. Keep the icons folder and both PNG icons in place.
4. Deploy to an HTTPS host (for example, Vercel). PWA installation requires HTTPS, except localhost during development.

INSTALL ON ANDROID
1. Open the deployed HTTPS website in Chrome.
2. Tap “Install Monavest App” on the welcome, login or sign-up screen.
3. Accept the browser installation prompt. If no prompt appears, use Chrome menu (⋮) > Install app / Add to Home screen.

INSTALL ON IPHONE / IPAD
1. Open the deployed HTTPS website in Safari.
2. Tap Share.
3. Choose Add to Home Screen, then tap Add.

The app opens in standalone/full-screen mode after installation. The service worker caches the app shell for offline launch; Tailwind CDN styling still requires internet access. Demo account data remains in that browser's local storage. This is not a real bank and does not process real payments.
