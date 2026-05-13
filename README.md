# MTJ Welding & Fabrication — Website

Official website for **MTJ Welding & Fabrication**, a firefighter-owned steel
shop in Salt Lake City offering custom fabrication, mobile welding repair,
and LiftMaster gate operator sales & install.

**Live site:** https://www.mtjwelding.com

## What's in this repo

```
.
├── index.html              # The entire website — single HTML file with embedded CSS & JS
├── CNAME                   # Tells GitHub Pages to serve www.mtjwelding.com
├── .nojekyll               # Disables Jekyll preprocessing (serves files as-is)
└── images/
    ├── IMG_*.jpg           # Project photos used in the gallery & hero
    ├── logo-icon.svg       # MTJ circle monogram (used as favicon)
    └── logo-wordmark.svg   # Full MTJ Welding & Fabrication wordmark
```

## How it's deployed

This repo is published with **GitHub Pages**. Settings → Pages →
*Deploy from a branch* → `main` / root.

Custom domain (`www.mtjwelding.com`) is configured via the `CNAME` file at the
repo root. HTTPS is provided automatically by GitHub via Let's Encrypt.

## Editing the site

Everything lives in `index.html`. To change copy, find the section comment
(e.g. `<!-- ===== HERO ===== -->`) and edit the text directly. To swap a photo,
drop a new file into `images/` and update the matching `<img src="">` line.

## Contact

- Phone / Text: 801-566-5412
- Email: mtjwelding@gmail.com
- Instagram: [@mtj_welding](https://instagram.com/mtj_welding)
