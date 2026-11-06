# kaygent.github.io

Organization GitHub Pages root for **Kaygent**.

This repository is intentionally tiny: it redirects the root domain to the
project site.

```
https://kaygent.github.io/  →  https://kaygent.github.io/kaygent/
```

The actual landing page lives in the project repository under `docs/` and is
deployed from `kaygent/kaygent` (**Settings → Pages → main / docs**).

## Setup

1. Create the public repository `kaygent/kaygent.github.io` on GitHub.
2. Push this repository's `main` branch to it.
3. Open **Settings → Pages** and set **Source** to **Deploy from a branch**,
   branch **main**, folder **/ (root)**.
4. Confirm the project site is enabled in `kaygent/kaygent` under **Pages** with
   the **/docs** folder.

`404.html` also redirects unknown root paths to the project site, so old or
mistyped URLs still land in the right place.

## Files

- `index.html` — root redirect with a branded fallback link
- `404.html` — redirect for unknown paths
- `styles.css` — shared styling for the redirect pages
- `assets/icon.svg` — Kaygent mark
