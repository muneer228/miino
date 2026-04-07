# Miino Pages starter pack

Copy these files into your site folder:

- `favicon.svg`
- `site.webmanifest`
- `_headers`
- `_redirects`
- `404.html`
- `robots.txt`

Then open `head-snippet.html` and paste those tags into the `<head>` of your `index.html`.

Git init / first push:

```bash
cd /home/axo/sites/miino
git init
git add .
git commit -m "Initial Miino Pages site"
```

In Cloudflare Pages:
- Connect to GitHub
- Framework preset: None
- Build command: leave empty
- Build output directory: `/`
- Add custom domains: `miino.xyz` and `www.miino.xyz`
