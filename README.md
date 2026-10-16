# Yadukrishna PB — portfolio

Personal portfolio site. A single static `index.html`: no build step, no dependencies besides Google Fonts.

## Projects featured

- [verified-tool](https://github.com/yadukpb/verified-tool) — stops AI agents re-running side effects after a lost response or crash
- Adaptive maths tutor — Bayesian Knowledge Tracing + prerequisite graph tutor for Class 3 maths
- Job portal and resume toolkit — job portal, ATS checker, listings tracker, LaTeX resume builder
- [Digital outpass system](https://github.com/yadukpb/college-outpass) — 1st prize, Velohack 1.0
- [Judge-Aware Eval Gate](https://github.com/yadukpb/judge-aware-eval-gate) — CI gate for LLM-agent evals using Dawid-Skene EM judge-reliability modeling + Sidak alpha-spending
- [ADHD screener & daily coach](https://github.com/yadukpb/adhd-screener) — research-based screening plus an AI coach, planner, focus timer and habit tracking

Keep this list in sync with the `#projects` section in `index.html` when either changes.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

## Publish on GitHub Pages

1. Push this repo to GitHub. Naming it `yadukpb.github.io` serves the site at https://yadukpb.github.io.
2. In the repo, go to **Settings → Pages**, set **Source** to *Deploy from a branch*, and pick `main` / `/ (root)`.

Works the same on Netlify or Cloudflare Pages: point them at the repo with no build command and `/` as the output directory.
