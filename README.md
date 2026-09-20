# Debasish Mohanty - portfolio

Single-page portfolio. Plain HTML, CSS and JavaScript. No build step, no dependencies.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site |
| `og-image.png` | Link-preview image (1200x630) for LinkedIn and WhatsApp |
| `CNAME` | Custom domain for GitHub Pages (`www.debasishmohanty.in`) |
| `resume.pdf` | **Add this yourself.** The Resume button links to it |

## Before you deploy

1. Put your resume in this folder as `resume.pdf`.
2. Optional: add GitHub links for SmartScaler, KubeRTSec and ZeroTrustOps
   inside the `Innovation` section of `index.html` (copy the
   `<p class="pr">` line from another entry).

## Deploy on GitHub Pages

1. Create a public repo and upload every file in this folder.
2. Settings > Pages > Deploy from a branch > `main` / root > Save.
3. Settings > Pages > Custom domain: `www.debasishmohanty.in` > Save.
4. In GoDaddy DNS add:
   - CNAME `www` -> `debasish-87.github.io`
   - A `@` -> `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
5. When available, tick Enforce HTTPS in Settings > Pages.

## Run locally

Open `index.html` in a browser. Fonts need an internet connection.
