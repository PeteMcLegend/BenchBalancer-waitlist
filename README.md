# BenchBalancer waitlist theme

Landing page for the BenchBalancer waitlist, packaged as a Shopify theme.

## Local preview
- Open `index.html` in a browser; assets live in `assets/`.

## Shopify upload
- Zip the contents of this folder (not the folder itself) so `assets/`, `layout/`, `templates/`, and `config/` sit at the root of the zip.
- In Shopify admin: Online Store → Themes → Add theme → Upload zip file, then pick the zip you created.
- Publish or preview the uploaded theme.

## Waitlist endpoint
- The form POSTs to `/api/waitlist`. Point that route to your waitlist handler (e.g., a Shopify app proxy, Shopify Function, or external endpoint) so submissions work in production.
