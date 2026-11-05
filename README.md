# GSD Gauge Control — iPhone Web App

Standalone static dashboard for the triple GC9A01 gauge project. Includes a simulated engine input, independent gauge customization, configurable warning thresholds, purple honeycomb faces, and mobile Safari support. This is a design simulator, not connected to an ECU or ESP32.

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `gsd-gauge-control`.
2. Upload `index.html` to the **root** of the repository (and optionally this README).
3. Open **Settings → Pages**, choose **Deploy from a branch**, `main`, `/(root)`, then Save.
4. Open `https://YOUR-USERNAME.github.io/gsd-gauge-control/` in iPhone Safari after deployment.
5. Use **Share → Add to Home Screen** if desired.

No frameworks, build tools, CDNs, or external fonts are required. The app is self-contained in `index.html`. Do not upload the ZIP as a single repository file; upload the extracted `index.html`.
