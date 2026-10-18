# VS-INVENTORY-MANAGEMENT

VaultSync POSM Inventory tool (installable phone app). GitHub Pages: https://rmas-ce.github.io/VS-INVENTORY-MANAGEMENT/

- `index.html` — the whole app. Data lives in the Google Sheet (Apps Script backend).
- `posm-org.js` — warehouse / region / Trade Supervisor / store starting list.
- `posm-data-1..6.js` — starting POSM list with pictures. Only loaded when a new Sheet is seeded or Admin uses "Replace POSM list".
- `sw.js` — offline helper. Change `VERSION` in it whenever you upload a new version so phones update.
