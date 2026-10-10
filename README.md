# Ramtin Soleymani — Hardware Engineering Portfolio

A responsive portfolio built with HTML, CSS, and vanilla JavaScript. It highlights
RTL, FPGA, CDC, design verification, computer architecture, and SystemC NoC work.

## Included pages

- `index.html` — main portfolio page
- `resume.html` — embedded hardware-focused resume with a direct PDF link
- `styles.css` — all styling
- `script.js` — mobile navigation, year update, and scroll animations
- `assets/ramtin-profile.jpg` — profile portrait
- `assets/ramtin-soleymani-resume.pdf` — current resume
- `assets/systemc-network-on-chip-engineering-report.pdf` — NoC engineering report
- `assets/fall-2025-deans-list-letter.pdf` — Fall 2025 Dean's List letter
- `assets/winter-2026-deans-list-letter.pdf` — Winter 2026 Dean's List letter
- `assets/favicon.svg` — simple site icon

## How to run locally

Open `index.html` directly in your browser, or use a simple local server.

Example with Python:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deployment

Pushing to `main` runs `.github/workflows/pages.yml`, which deploys the repository
to GitHub Pages.

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
│   ├── ramtin-profile.jpg
│   ├── ramtin-soleymani-resume.pdf
│   ├── systemc-network-on-chip-engineering-report.pdf
│   ├── fall-2025-deans-list-letter.pdf
│   └── winter-2026-deans-list-letter.pdf
├── index.html
├── README.md
├── resume.html
├── script.js
└── styles.css
```
