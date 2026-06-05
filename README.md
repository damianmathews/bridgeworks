# Bridgeworks

AI for the asset management cycle. Sourcing, diligence, quarterly valuation, portfolio monitoring, LP reporting.

This repo holds the public marketing site for Bridgeworks. Static HTML, no build step required.

## Pages

- `index.html` — home. Hero, the five-phase asset management cycle, six-section output package, the WROTE / CONFIRMED / FLAGGED model, case study summary, approach, capacity form, FAQ.
- `about.html` — about the firm. Founder note, principles, anti-positioning, team.
- `work/farol.html` — long-form case study, anonymized PE asset manager engagement.
- `thanks.html` — diagnostic-form submission confirmation page. Targeted by Netlify form action.
- `og.html` — screenshot-ready 1200×630 social card. Open in browser, screenshot, save as `assets/og-image.png`.
- `outreach/` — internal outbound playbook, message templates, and banked LinkedIn posts. Not deployed publicly (robots.txt disallow).

## Local preview

```bash
# any static server works; for example
cd bridgeworks
python3 -m http.server 8080
# then open http://localhost:8080
```

Or just `open index.html` to preview directly from the filesystem.

## Deploy to Netlify

This site deploys with zero configuration.

**Option A — drag and drop (fastest)**

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `bridgeworks` folder onto the page
3. Netlify deploys instantly to a generated `*.netlify.app` URL
4. Connect a custom domain in Site settings → Domain management

**Option B — GitHub continuous deployment (recommended)**

1. Go to [app.netlify.com](https://app.netlify.com), click **Add new site → Import an existing project**
2. Connect GitHub, pick this repo
3. Build settings: leave **build command empty**, **publish directory** is the repo root (`.` or empty)
4. Click Deploy
5. Every push to `main` auto-deploys

**Forms (Netlify Forms)**

The diagnostic form in `index.html` is wired with `data-netlify="true"` and the hidden `form-name` input. Netlify auto-detects it on first deploy. Submissions land in Site dashboard → **Forms** → `diagnostic`. To get email notifications, configure under Forms → Settings → Form notifications.

## Stack

- Static HTML, no framework
- Fraunces (serif display) + Inter (body) + JetBrains Mono (data) via Google Fonts
- Single accent color (deep green `#6CA98A`) on a dark `#0A0B0D` ink base
- Vanilla JS for FAQ accordion, anchor-scroll offset, active-nav highlight, and scroll reveal
- No build step. No dependencies. Open and read the source.

## Brand voice rules

These are enforced across every page. Anything that violates them gets cut.

- No em dashes
- No "X, not Y" tropes ("it's not a tool, it's a partner")
- No "leverage", "unlock", "transform", "synergies", "robust", "underscores"
- No platitudes about AI being revolutionary
- Every claim should be falsifiable. Every figure should trace to source.
- The word "AI" appears no more than 4 times above the fold.

## License

Proprietary. © 2026 Bridgeworks. Code and copy not licensed for reuse.
