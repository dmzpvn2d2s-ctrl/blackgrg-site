# BLACK GRG — static protected build

Single-file page for GitHub Pages. All styles, scripts, images, stickers and
fonts are embedded inside `index.html`; the markup is XOR-encoded and decoded
in the browser, so `view-source` does not expose the design.

- `index.html` — the whole site (~2.2 MB, no external requests)
- `404.html` — redirects unknown paths to home
- `.nojekyll` — disables Jekyll processing

Custom domain (is-a.dev) will be added via the `CNAME` file once the
subdomain pull request is merged.
