# munajaatpress.com

The website of Munajaat Press: plain HTML and CSS, no build step, no cookies, no tracking. Visitor counts come from Cloudflare Web Analytics (cookie-free), switched on in the Pages project under Metrics, which adds the beacon automatically at deploy.
Hosted on Cloudflare Pages from this repository's `main` branch.

- `index.html` – home page with all the books
- `privacy.html`, `404.html`
- `css/style.css`
- `fonts/` – self-hosted subsets of Noto Serif and Amiri (SIL Open Font License; see `fonts/`)
- `images/` – covers, logo, Readers' Favorite seal
- `downloads/` – free colouring sample PDF

To add a book: copy one `<article class="book">` block in `index.html`, add its cover to `images/books/`, and update the Amazon links.
