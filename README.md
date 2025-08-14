# LensCraft Studio — Static Website

A simple, static website for a boutique photography studio. Built with plain HTML, CSS, and minimal JS so it works out-of-the-box on GitHub Pages.

## Structure
- `index.html` — Home
- `services.html` — Services & pricing
- `portfolio.html` — Image gallery
- `about.html` — Studio info
- `contact.html` — Contact form (Formspree) & map
- `assets/css/styles.css` — Styles
- `assets/js/main.js` — Small JS (copyright year)

## Run locally
Open `index.html` in your browser, or use a simple server:
```bash
# Python 3
python -m http.server 8000
# Visit http://localhost:8000
```

## Deploy (GitHub Pages)
1. Create a new GitHub repo (public).
2. Upload all files from this folder (or push via git).
3. In **Settings → Pages**, set **Source** to `main` branch, folder `/root`.
4. Your site will publish to `https://<username>.github.io/<repo-name>/`.

## Customization
- Replace images with your own (local files or hosted URLs).
- Update copy, services, and pricing.
- Change contact form endpoint in `contact.html` (replace the Formspree URL with your own form handler).

## License
MIT. See `LICENSE`.
