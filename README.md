# nit-site

Nit's public pages moved to https://bkrem.github.io/nit/. Their source lives in the `nit/` folder of [bkrem/bkrem.github.io](https://github.com/bkrem/bkrem.github.io).

This repository serves redirects only, so links to the old https://bkrem.github.io/nit-site/ URLs keep working:

- `index.html`, `privacy/index.html`, `support/index.html`, and `faq/index.html` redirect to the matching page under `/nit/`, keeping the query string and fragment.
- `404.html` maps any other `/nit-site/<path>` to `/nit/<path>`.
- `assets/og.png` stays so link previews that cached the old image URL still load.
