# Taxation Clinic website

A static, multi-page website for Taxation Clinic, a tax advisory firm serving Farrukhabad–Fatehgarh, Uttar Pradesh.

## Run locally

This project uses plain HTML, CSS and JavaScript; no package installation is required. From this directory, run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Implemented pages

- `index.html` — homepage
- `about.html` — firm approach
- `services.html` — service overview
- `services/income-tax.html` — Income Tax Returns
- `services/gst.html` — GST services
- `services/tds.html` — TDS services
- `services/business-compliance.html` — Business Tax & Compliance
- `resources.html` — general guidance and official references
- `contact.html` — local enquiry-draft generator (does not send or store data)
- `privacy-policy.html`, `terms.html`, `cookies.html` — working drafts requiring review
- `thank-you.html` — reserved explanatory page; no submission is implied
- `404.html` — branded static not-found page

## Before production launch

1. Verify whether `taxationclinic.in` is available and owned. It is currently a proposed domain only. Update canonical URLs, sitemap, robots.txt and Open Graph URLs to the confirmed production domain.
2. Add verified phone, email, address, hours and any approved social profiles.
3. Verify the owner's qualifications and the exact services permitted within the practice. Do not add unverified designations, testimonials or claims.
4. Configure a real contact form delivery provider and test delivery end-to-end. The current form only prepares a local text draft.
5. Review and finalize privacy, terms and cookie information against actual hosting, data practices and applicable law.
6. Decide whether to self-host fonts or retain Google Fonts; review third-party requests and applicable consent obligations.
7. Validate all metadata, schema, links, responsive behavior, accessibility and performance in the intended production environment.
8. Configure Google Search Console and submit the verified sitemap after deployment.

## Known launch blockers

- Production domain is not confirmed; canonical URLs and sitemap use `https://taxationclinic.in` provisionally.
- Public contact details are missing.
- Contact form delivery backend and recipient are not configured.
- Privacy and legal drafts require review.
- Owner credentials, professional profile, service scope and pricing/fee policy are not yet verified.
- No production deployment, search indexing, analytics, form delivery or third-party integration is claimed.

## Design system

- Forest green `#173D32`
- Warm ivory `#F8F4E9`
- Muted gold `#B39A64`
- Ink charcoal `#292F2B`
- Sage grey `#E5EBE4`
- Headings: Lora; body: Inter; Hindi: Noto Sans Devanagari (Google Fonts fallback)


## Hindi / English language toggle

The header includes a Hindi/English toggle. Hindi translations are provided locally in `assets/language.js`; the selected language is remembered in browser storage where available. No external translation API is used. Review translations and any unmapped copy before publishing.
