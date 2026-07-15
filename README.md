# SeaWorld Dosage Calculators PWA

Includes:
- Soda Ash calculator
- Manual Chlorine Feed calculator
- CYA dosing calculator
- CYA sensor-calibration alerts
- SeaWorld-themed aquatic styling
- Offline support after initial load

## Update the existing GitHub Pages site
Replace the files in the repository root with:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png

Commit the changes to the `main` branch. GitHub Pages will republish automatically.

The service-worker cache name is `seaworld-dosage-v8`, which forces installed copies to refresh after the hosted page is reopened in Safari.
