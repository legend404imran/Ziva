# Zayumi Jewels storefront (static)
Deploy: push this folder to GitHub, connect to Netlify (no build command, publish directory `/`).
Edit `data/config.json` (business details), `data/products.json` (fields explained in `_doc`) and `data/pages.json` (About/Contact/policy text: review before launch).
Replace `YOUR-SITE.netlify.app` in the HTML files, sitemap.xml and robots.txt with your real domain.
Photos go in `assets/products/` (paths as in products.json); add `assets/images/hero.jpg` and your UPI QR as `assets/icons/upi-qr.png`. Missing images show a placeholder.
Cart, wishlist and saved checkout details live only in the visitor's browser (LocalStorage).
The invoice admin is a browser-only tool: its password lock is NOT real security, and invoices live only in that browser. Export JSON backups regularly and keep your PDFs.
