# sonderrift.github.io

Host-root GitHub Pages site for `sonderrift.github.io`.

Exists for one reason: a `robots.txt` is only honoured at the **host root**, and a
GitHub *project* page (`/speak-like-yourself/`) cannot serve one. Without this repo
`https://sonderrift.github.io/robots.txt` was a 404, so there was no `Sitemap:`
declaration anywhere on the host and no sitemap auto-discovery for Google.

Contents:

- `robots.txt` — allow-all plus the two `Sitemap:` lines for the blog.
- `index.html` — a `noindex` placeholder so the root is not a 404 page.
