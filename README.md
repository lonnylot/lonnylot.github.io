# lonnylot.com

Personal landing page for [Lonny Lot](https://lonnylot.com) — links to projects and social.

**Live:** https://lonnylot.com  
**Hosted on:** Cloudflare Workers (static assets)  
**Workers.dev:** https://lonnylot.lonny-e64.workers.dev  

## Contents

| Path | Purpose |
|------|---------|
| `public/index.html` | Landing page |
| `public/robots.txt` | Allow all crawlers |
| `public/llms.txt` | Machine-readable about page for LLMs |
| `public/_headers` | Security / cache headers |
| `wrangler.toml` | Cloudflare Worker deploy config |

## Local preview

```bash
npx --yes serve public
```

## Deploy

```bash
npx wrangler deploy
```

Serves `lonnylot.com/*` and `www.lonnylot.com/*` via Worker routes on the Cloudflare zone.

## Projects linked

- [Space Cadet](https://space-cadet.lonnylot.com)
- [macOS 27](https://macos27.lonnylot.com)
- [X @lonnylot](https://x.com/lonnylot)
