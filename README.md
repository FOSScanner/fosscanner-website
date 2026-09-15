# FOSScanner website

The public landing page for [FOSScanner](https://github.com/FOSScanner/fosscanner-app), a privacy-first, free and open-source document scanner.

This is a dependency-free static site designed for GitHub Pages. The page is intentionally small, readable, and focused on the product's privacy promise.

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Deployment

The `deploy-pages.yml` workflow publishes the repository to GitHub Pages whenever `main` changes.
