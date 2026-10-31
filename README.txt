NIET IT DEPARTMENT DIGITAL MAGAZINE — DEPLOYMENT

Files:
- index.html: responsive magazine reader website
- assets/it-department-magazine-2025-26.pdf: supplied 42-page PDF

FREE HOSTING (Vercel):
1. Extract this ZIP on your computer.
2. Create/sign in to a Vercel account.
3. Choose Add New > Project > Deploy from template / upload project (or import a Git repository).
   Easiest reliable method: create a GitHub repository, upload the extracted folder contents, then import that repository into Vercel.
4. Keep index.html at the project root and the assets folder beside it.
5. Framework preset: Other. Build command: leave blank. Output directory: leave blank (or ./).
6. Deploy. Vercel will provide a public URL ending in vercel.app.
7. Test the URL on a phone before printing any QR code.

IMPORTANT:
- The site is self-hosted as your own website; it does not show Heyzine/Flipsnack branding.
- The reader loads the open-source PDF.js library from a CDN. The magazine PDF itself is served from your website.
- The public URL and QR code can only be finalized after deployment. Do not print a QR code before the URL is live.
- This package uses the supplied Session 2025-26 magazine PDF. Replace the PDF in assets and keep the same filename to publish a later edition.
