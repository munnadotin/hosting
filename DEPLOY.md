# Softantra website deployment

This bundle contains:

- `index.html` — responsive bilingual global outsourcing homepage
- `robots.txt` — allows search-engine crawling and points to the sitemap
- `sitemap.xml` — current public URLs for search engines
- `DEPLOY.md` — publishing guidance

## Homepage positioning

The homepage positions Softantra as a Japanese-English global outsourcing company focused on:

- IT Support Outsourcing
- Accounting & Bookkeeping Outsourcing
- Bilingual Business Operations
- Experienced personnel and transparent delivery responsibilities
- Client-aligned data security and confidentiality controls
- Global support focus: Japan, USA, UK, Canada, Australia and India

The EN / 日本語 buttons switch the page language in place.

## Before publishing

The contact form is configured for `contact@softantra.com` and opens the visitor's mail application.

Review all experience, qualification and security statements before publishing. Only add formal credentials,
certifications, compliance claims, client names or quantified experience after they have been verified.

## Hosting recommendation

For reliable loading and SEO control, publish these files on a static host such as Cloudflare Pages,
Netlify, Vercel or GitHub Pages, then point `www.softantra.com` to that host.

If migrating away from the current website host, do not remove Google Workspace MX/TXT records used
for email. Change only the DNS records required for the website host.

## Search after deployment

1. Confirm `https://www.softantra.com/` loads correctly on desktop and mobile.
2. Confirm both EN and 日本語 buttons work.
3. Test the contact email flow.
4. Confirm `https://www.softantra.com/robots.txt` and `/sitemap.xml` load.
5. In Google Search Console, inspect the homepage and request indexing.
6. Submit `https://www.softantra.com/sitemap.xml`.

## Future brochures

When service brochures are ready, add public pages or PDFs such as:

- `brochures/it-support.html`
- `brochures/accounting-bookkeeping.html`
- `brochures/data-security.html`

Only add live public URLs to `sitemap.xml`.
