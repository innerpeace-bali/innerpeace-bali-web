# INNerpeace Bali — Website

**Less Noise, More Peace.** Official website for INNerpeace Villa (private ricefield villas for short stays) and INNerpeace Residence (quiet monthly rooms for working professionals) in Celuk, Sukawati, Gianyar, Bali.

**Live:** https://www.innerpeacebali.com

## Features

- Bilingual pages — English (`/`) and Bahasa Indonesia (`/id/`) with `hreflang`
- Separate sections for Villa (overview, facilities, contact) and Residence (overview, contact)
- Editable prices, facilities, FAQ, and contact details via a Git-based CMS at `/admin/` (`data/*.json`)
- Schema.org JSON-LD, Open Graph, sitemap, and custom 404 page

## Tech Stack

- Plain HTML, CSS, and vanilla JavaScript — no build step
- Hosted on Cloudflare Workers Static Assets (`wrangler.jsonc`), security headers in `_headers`
- Decap CMS with GitHub backend for content editing

## Run Locally

No install needed. Serve the folder with any static server, for example:

```bash
npx serve .
```

Then open http://localhost:3000.

## Deploy

Pushing to `main` triggers the Cloudflare build connected to this repository.

## License

© 2026 INNerpeace Bali. All rights reserved. Built by Anabhi Dev.
