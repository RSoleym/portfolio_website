# Personal Portfolio Website

A clean one-page portfolio website built with HTML, CSS, and vanilla JavaScript.

## Included pages

- `index.html` — main portfolio page
- `resume.html` — temporary resume page so the Resume button works immediately
- `styles.css` — all styling
- `script.js` — mobile navigation, year update, and scroll animations
- `assets/profile-placeholder.svg` — placeholder portrait image
- `assets/favicon.svg` — simple site icon

## Quick edits to make first

1. Replace `assets/profile-placeholder.svg` with your actual photo.
2. Update the LinkedIn link in `index.html`.
3. Replace the placeholder project text with your final project summaries and links.
4. Swap `resume.html` for your real resume flow.

## How to run locally

Open `index.html` directly in your browser, or use a simple local server.

Example with Python:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Suggested deployment

### GitHub

1. Create a new repository.
2. Upload all files from this folder to the root of the repo.
3. Commit and push to `main`.

### Cloudflare Pages

1. Connect your GitHub repository to Cloudflare Pages.
2. Choose the repository.
3. Use these settings:
   - Framework preset: `None`
   - Build command: leave blank
   - Build output directory: leave blank
4. Deploy.

## Customisation notes

- Main accent colour: `#C4C5BA`
- Main background: dark charcoal
- Font: Outfit from Google Fonts
- Navigation items: About Me, Highlighted Projects, Accomplishments, Contact

## Project structure

```text
portfolio_site/
├── assets/
│   ├── favicon.svg
│   └── profile-placeholder.svg
├── index.html
├── README.md
├── resume.html
├── script.js
└── styles.css
```
