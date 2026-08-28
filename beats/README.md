# 20 Studios Beat Store — fixed

IMPORTANT: `beats.html` now works by itself. It contains a fallback catalog, so it will NOT show "Catalog could not be loaded" if `beats.json` is missing.

Files:
- beats.html — upload this file and the store will load.
- beats.json — optional external catalog. If present beside beats.html and valid, it overrides the fallback catalog.
- README.md

Recommended deployment:
1. Put `beats.html` at the desired `/beats/` path.
2. Put `beats.json` in the SAME directory if you want to edit the catalog separately.
3. If Netlify only receives beats.html, it still works.
4. For your real catalog, replace the sample objects in beats.json. The page can continue to use beats.json automatically.

Note: This is still a frontend/catalog layer. Paystack verification and secure MEGA delivery should be added server-side before accepting real orders.
