# FOSScanner website

The official public website for [FOSScanner](https://github.com/FOSScanner/fosscanner-app), a privacy-first, free and open-source document scanner.

Live site: <https://fosscanner.github.io/fosscanner-website/>

## What this repository contains

This is a lightweight, dependency-free static landing page focused on the product’s core message:

- document scanning and PDF export on the device;
- no accounts, tracking, cloud storage, or remote processing;
- open-source development and transparent project links.

The site is built with semantic HTML and responsive CSS. It does not require a JavaScript framework, package manager, or third-party runtime service.

## Repository structure

- `index.html` — page content and metadata
- `styles.css` — layout, responsive behavior, and visual styling
- `assets/` — static media used by the page
- `.github/workflows/deploy-pages.yml` — GitHub Pages deployment workflow

## Deployment

The `Deploy website` workflow publishes the `main` branch to GitHub Pages after every push. Deployment status and history are available in the repository’s Actions tab.

## Contributing

Keep the site simple, accessible, responsive, and consistent with FOSScanner’s privacy-first identity. Avoid adding analytics, external tracking, or unnecessary runtime dependencies.
