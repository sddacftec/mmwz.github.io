## Cursor Cloud specific instructions

This is a minimal static GitHub Pages site (`mmwz.github.io`). The entire product is a single `index.html` file — no dependencies, no build tools, no package manager, no tests, no linting.

### Running locally

Serve the site with any static HTTP server:

```
python3 -m http.server 8080
```

Then open `http://localhost:8080/` in a browser.

### Notes

- No `package.json`, `requirements.txt`, or other dependency manifests exist.
- No build step, transpilation, or bundler is used.
- No automated tests or lint configuration exist in the repo.
- Changes to `index.html` are immediately reflected on reload when using a local server.
