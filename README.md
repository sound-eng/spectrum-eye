# Spectrum Eye website

Public web presence for [Spectrum Eye](https://www.spectrum-eye.com/) — the iOS real-time analyzer (RTA), SPL meter, and spectrogram for iPhone and iPad.

The repo used to contain only the privacy policy at the root; it now also includes the marketing site under `docs/` (served via GitHub Pages) and source artwork used to build `docs/assets/`.

## What’s in the repo

| Path | Purpose |
|------|---------|
| `docs/` | **Published site** — HTML, CSS, JS, and web images (GitHub Pages source) |
| Root `*.png`, `sp-icon.png`, etc. | Full-resolution screenshots and sources used to regenerate `docs/assets/img/` |
| `social.txt` | Social and community URLs referenced on the site |
| `spectrum_eye_privacy_policy_en.md` | Privacy policy source; the live page is `docs/se_privacy_policy_en.html` |

## GitHub Pages

1. **Settings → Pages**
2. Build from branch **`main`**, folder **`/docs`**
3. Optional custom domain: `www.spectrum-eye.com` (add `docs/CNAME` and DNS as GitHub describes)

## Local preview

```bash
cd docs && python3 -m http.server 8000
```

Open [http://localhost:8000/](http://localhost:8000/).

The App Store listing is linked from the site with campaign tag `ct=website`.
