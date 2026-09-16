# Spectrum Eye website

Public web presence for [Spectrum Eye](https://www.spectrum-eye.com/) — the iOS real-time analyzer (RTA), SPL meter, and spectrogram for iPhone and iPad.

Everything published on GitHub Pages lives under `docs/`. The repository root only adds this README.

```
.
├── README.md
└── docs/
    ├── .nojekyll
    ├── index.html
    ├── features.html
    ├── se_privacy_policy_en.html
    └── assets/
        ├── css/site.css
        ├── js/site.js
        └── img/          # hero, logo, favicons, App Store badges, screenshots
```

Social links (Facebook, WhatsApp, UserJot) are in the footers of `docs/index.html` and `docs/features.html`. App Store URLs use campaign tag `ct=website`.

## GitHub Pages

1. **Settings → Pages**
2. Build from branch **`main`**, folder **`/docs`**
3. Optional custom domain: `www.spectrum-eye.com` (add `docs/CNAME` and DNS as GitHub describes)

## Local preview

```bash
cd docs && python3 -m http.server 8000
```

Open [http://localhost:8000/](http://localhost:8000/).
