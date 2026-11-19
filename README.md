# Crossword Time

Free static website with two rotating playable mini crossword puzzles, vocabulary cards, SEO metadata, and placeholders for Android/iOS store links.

## Deploy with Cloudflare Pages

1. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git.
2. Authorize GitHub and select `pamelatd27/crossword-time`, branch `main`.
3. Framework preset: None. Build command: `exit 0`. Build output directory: `/` (repository root).
4. Deploy and visit the assigned `pages.dev` URL.

No Node installation or build pipeline is required. Cloudflare Pages serves the HTML, CSS, and JS files directly.

## Local preview

Run `python3 -m http.server 8000` and open http://localhost:8000.

## Before broader promotion

- Add real Google Play and App Store links, app screenshots, and support contact.
- Review the privacy page.
- Add more original puzzles and vocabulary pages; current daily challenges rotate between two puzzles, not a unique puzzle every day.
- Configure a verified custom domain, canonical tags, and XML sitemap.
- Test browser behavior, accessibility, and Search Console indexing after deployment.
