# lonnylot.com

Personal landing page for [Lonny Lot](https://lonnylot.com) — links to projects and social.

**Live:** https://lonnylot.com  
**Hosted on:** [Cloudflare Pages](https://dash.cloudflare.com) (`lonnylot` project)  
**Preview:** https://lonnylot.pages.dev  

## Contents

| Path | Purpose |
|------|---------|
| `public/index.html` | Landing page |
| `public/robots.txt` | Allow all crawlers |
| `public/llms.txt` | Machine-readable about page for LLMs |
| `public/_headers` | Security / cache headers |
| `wrangler.toml` | Cloudflare Pages config |

## Local preview

```bash
npx --yes serve public
```

## Deploy

```bash
npx wrangler pages deploy public --project-name=lonnylot --branch=master
```

Custom domains: `lonnylot.com` and `www.lonnylot.com` (DNS CNAMEs → `lonnylot.pages.dev`, proxied).

## Projects linked

- [Space Cadet](https://space-cadet.lonnylot.com)
- [macOS 27](https://macos27.lonnylot.com)
- [Is it SOTA?](https://isitsota.com)
- [Quiet Neighbor](https://github.com/lonnylot/QuietNeighbor)
- [X @lonnylot](https://x.com/lonnylot)
