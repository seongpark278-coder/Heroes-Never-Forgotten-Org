# Heroes-Never-Forgotten-Org
501 (c)(3) non-profit organization

A responsive website supporting veterans, active-duty personnel, domestic violence survivors, firefighters, first responders, and their families.

## Preview

Serve this directory with any static HTTP server, or open `index.html` in a browser.

## Hosting

The site uses plain HTML, CSS, JavaScript, and SVG. No build step is required. On Vercel, select the Other framework preset, leave the build command empty, and use the repository root as the output directory.

## Donations

The Donate button links to the supplied PayPal payment page. Suggested amounts are informational; the donor chooses the final amount on PayPal. The site uses a direct PayPal payment link and does not load the PayPal SDK.

No banking account numbers or credentials are included in this repository.

## SEO

Each public page has a unique title and description, a canonical URL, social sharing metadata, and JSON-LD identifying the organization and website. The homepage canonical is https://www.heroesneverforgotten.org/; Vercel redirects /index.html to /. Keep sitemap.xml canonical URLs and last-modified dates aligned with actual page updates.

The homepage serves a lossless WebP photo with the original PNG fallback. Avoid adding tracking or external payment SDKs unless the corresponding feature actually needs them.

After publication, submit https://www.heroesneverforgotten.org/sitemap.xml in the verified Google Search Console property and inspect the canonical homepage URL. Search Console ownership, sitemap submission, crawling, and indexing status must be verified in that account; publishing source does not prove indexing.
