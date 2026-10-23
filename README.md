# DXB Staff Wayfinder — Terminal 1 Concourse D

A fresh, standalone PWA starter that uses DXB Staff Wayfinder as a visual/product reference and the supplied Concourse D PDF as the initial gate/facility source.

## Included
- Search across gates and facility names, with exact gate matches prioritized.
- Category filter: All, Gate, Restrooms, Food & Drink, Shopping, Services.
- Quick Tiles for Airport Community, Express Map, and Pocket Flight.
- Installable PWA manifest and offline service worker.
- Separate data bundle and cache name for the Terminal 1 project.

## Important setup notes
- The three Quick Tiles are present, but their destinations are placeholders until official URLs / service endpoints are supplied.
- This starter does not copy the original site's Firebase credentials, admin system, QR destination links, or live flight API.
- Facility descriptions are based on the supplied Concourse D reference PDF. Verify operational details before publishing for passenger use.
- To publish on GitHub Pages, upload these files to a **new repository** and enable **Settings → Pages** for the default branch and root folder.
