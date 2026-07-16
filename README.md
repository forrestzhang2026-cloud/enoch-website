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

Hosted as a static site on Cloudflare Pages, custom domain `enochlogistics.com`.
Any push to the `main` branch auto-deploys.
