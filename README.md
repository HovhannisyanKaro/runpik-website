# Runpik website

Marketing landing + legal pages for Runpik — https://runpik.com.

Pure static HTML, no build step. Hosted on Cloudflare Pages, auto-deployed on push to `main`.

## Structure

| File | Purpose |
|---|---|
| `index.html` | Landing page |
| `terms.html` | Terms of Service |
| `privacy.html` | Privacy Policy |
| `style.css` | Shared minimal stylesheet |

## Local preview

Just open any `.html` file directly in a browser — no server needed.

For a tiny local server (useful if you want clean URLs):

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploy

Push to `main` → Cloudflare Pages picks it up automatically (~30 seconds).
