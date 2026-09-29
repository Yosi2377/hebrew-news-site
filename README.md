# חדשות הצפון (Hebrew news site)

Static Hebrew news aggregator.

## Live URL (Cloudflare quick tunnel)

**https://journalist-counties-structures-something.trycloudflare.com**

Verified HTTP 200 with Hebrew content and `data/latest.json`.

## Source

Deploy from `/workspace/news-site/public` (index.html, app.js, styles.css, data/latest.json).

## Notes

- Netlify anonymous deploy hit daily limit; Surge requires login.
- This tunnel stays up while the box keeps `python3 -m http.server` + `cloudflared` running.
- GitHub Pages: enable Pages on this repo (Settings → Pages → Deploy from branch `main` / root) after remaining assets are pushed for a durable `*.github.io` URL.
