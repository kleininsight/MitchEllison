# Running Rabbit Realty

Responsive static landing page for runningrabbitrealty.com, based on the approved ivory-and-charcoal mockup. Plain HTML, CSS, and JavaScript; no build dependencies or tracking.

## Preview

Run `python -m http.server 8000` from this directory, then open http://localhost:8000. The page also works by opening index.html directly.

## Content status

- Original supplied Running Rabbit Realty logo is included locally.
- Property photograph is generated illustrative imagery, not an actual listing. The page labels it accordingly.
- Email, telephone, brokerage, and DRE license details are intentionally TBD, as requested. Contact links go to the contact section; no inquiries are collected or falsely reported as sent.
- Search indexing is disabled with a robots meta tag while these details are incomplete. Remove that tag when the page is ready for public marketing.
- Add verified contact details and appropriate brokerage disclosures before launch. Replace illustrative property imagery with licensed regional or property photography when available.

## Hosting

Serve the repository root with any static host. GitHub Pages supports deploying from the main branch root using repository Settings > Pages. The CNAME file declares runningrabbitrealty.com; DNS and HTTPS must be configured at the hosting provider before the domain will work. No DNS or GitHub Pages settings are changed by this source update.

## Files

- index.html: content, navigation, contact placeholders, and metadata
- styles.css: responsive layout, focus styles, and reduced-motion support
- site.js: accessible mobile menu and footer year
- assets/logo.jpg: supplied logo
- assets/foothills-home.jpg: illustrative hero and section imagery

No forms, analytics, remote fonts, libraries, or third-party image requests are used.
