# Yadukrishna PB — portfolio

Personal portfolio site. A single static `index.html`: no build step, no dependencies besides Google Fonts.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Publish on GitHub Pages

1. Push this repo to GitHub. Naming it `yadukpb.github.io` serves the site at https://yadukpb.github.io.
2. In the repo, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, and pick `main` / `/ (root)`.

Works the same on Netlify or Cloudflare Pages: point them at the repo with no build command and `/` as the output directory.
