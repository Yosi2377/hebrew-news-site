# חדשות הצפון (Hebrew news site)

Static Hebrew news aggregator.

## Live URL

**https://wily-harbor-377.harvis.page**

Deployed with `npx harvis` (no login). Verified HTTP 200, Hebrew `lang="he"`/`dir="rtl"`, and `data/latest.json`.

Claim (private, single-use): https://harvis.dev/claim/81f67824-4846-4cd8-a6a5-7056cb08254e  
Unclaimed sites expire after 24 hours; redeploy updates the same subdomain.

Backup tunnel (while box processes run): https://journalist-counties-structures-something.trycloudflare.com

## Source

`/workspace/news-site/public` — index.html, app.js, styles.css, data/latest.json

Repo: partial (index.html + README). Enable GitHub Pages after pushing remaining assets if you want `*.github.io`.
