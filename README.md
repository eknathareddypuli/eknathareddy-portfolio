# eknathareddy.com

Personal portfolio of Eknatha Reddy Puli — Platform Engineering & SRE.
Hand-written HTML. No framework, no build step, no analytics, no cookies.

## Files

| Path | Purpose |
|---|---|
| `index.html` | The whole site (HTML + CSS + JS) |
| `og.png` | Social preview image (1200×630) |
| `favicon.svg` | Favicon |
| `404.html` | Custom not-found page (GitHub Pages serves it automatically) |
| `robots.txt`, `sitemap.xml` | Crawler hints |
| `.well-known/security.txt` | Security contact (RFC 9116) |
| `.nojekyll` | Stops GitHub Pages hiding `.well-known` |
| `demos/` | Drop demo MP4s here (see below) |
| `resume.pdf` | **Add yourself** — the Download résumé button points here |

## Edit before publishing

1. `index.html` → top of the `<script>`: set `EMAIL_USER` and `EMAIL_HOST`.
2. Replace every amber placeholder (`[N]`, `[edit …]`) with real, sanitised numbers.
3. Fill in cert years and verify links (`CERTS`), and adjust toolchain depth (`TOOLS`).
4. `.well-known/security.txt` → set a real `Contact:`; renew `Expires:` before it lapses.
5. Add `resume.pdf` at the repo root.

## Demo videos

Muted, ~30 s, H.264, under 2 MB each, named:
`demos/kubedrill.mp4`, `demos/chaoslab.mp4`, `demos/bimba.mp4`, `demos/resumelytics.mp4`, `demos/marga.mp4`.
Until a file exists, the card plays an animated placeholder.

## Easter eggs

Press **Ctrl/⌘ + K** for the command palette. Try the terminal's `help`. The classic cheat code also works.

## Deploy

GitHub Pages → Settings → Pages → deploy from `main` / root. Keep your existing `CNAME` file.
