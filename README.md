# Ningbo Enoch Global Forwarding — Company Website

Bilingual (EN / 中文) single-page marketing site for **Ningbo Enoch Global Forwarding Co., Ltd**
(宁波坤马国际货运代理有限公司).

- Single static file: `index.html` (inline CSS + JS, no build step).
- Assets: `logo.png`, `wechat-qr.png`.
- Quote form submits via the visitor's own email client (`mailto:`), no backend required.

## Local preview

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

Hosted on GitHub Pages from the `gh-pages` branch, custom domain `www.enochlogistics.com`
(set in `CNAME`). Any push to `gh-pages` auto-deploys.

DNS is managed at Aliyun: `www` is a CNAME to `forrestzhang2026-cloud.github.io`, and the
apex `enochlogistics.com` has A records for GitHub Pages (185.199.108-111.153), which redirect
to `www`. HTTPS is enforced in the repo's Pages settings.
