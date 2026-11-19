# Global Health Avenues website

A lightweight, static website for Global Health Avenues (GHA), an international medical education facilitation and coordination organisation. GHA connects physicians and healthcare institutions; it is not a hospital, clinical training provider or accrediting body.

## Pages

- `index.html` — positioning, programme formats and audience paths
- `physicians.html` — physician information and existing Google enquiry form
- `institutions.html` — institutional information and existing Google enquiry form
- `privacy.html` and `terms.html` — website notices
- `assets/site.css` and `assets/site.js` — shared responsive styling and accessible mobile navigation
- `robots.txt`, `sitemap.xml`, `favicon.svg` — discoverability and browser foundations
- `ops/ai-workflows/` — review-first, non-automated internal AI workflow guides

## Publishing notes

The pages are static HTML and can be served from a static Cloudflare Worker or Pages project. The current public preview uses `global-health-avenues.arunbhatia-ab.workers.dev` in canonical and sitemap URLs. After `globalhealthavenues.com` is connected and serves this site, update canonical metadata, Open Graph URLs, `robots.txt`, and `sitemap.xml` together. No DNS settings are changed by this repository.

The current physician and institutional Google Forms are embedded on their respective pages with direct fallback links. Keep both form IDs unchanged unless the form owner intentionally replaces them. Do not submit test responses to the live forms; use preview/read-only checks for launch verification.

## Brand and factual boundaries

The site retains GHA’s teal and gold visual identity and its facilitation positioning. Initial source markets are Nigeria, Kenya and Ethiopia; potential destinations being explored include India, Canada, the United States, the United Kingdom and Europe. These are strategic focus areas, not confirmed relationships or available placements.

Observerships are observational. Any hands-on activity is separate and requires express host approval, credentialing, supervision, insurance and compliance with local requirements. No placement, accreditation or practice privileges are promised.

## AI workflow guides

The workflow documents are prompts for human-run, review-first work. They do not connect to APIs, email, forms or a CRM; they do not send messages or collect sensitive information and do not incur service costs. A human must review research and all proposed content or enquiry classifications.
