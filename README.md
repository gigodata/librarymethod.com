# Library Method™ — librarymethod.com

> **Know your story. Trust your data. Act with clarity.**

The official public website for **Library Method™**, a proprietary methodology
of **GIGO Data, Inc.**

---

## About

The **Library Method™** is a structured, human-aware system for organising and
verifying data so you can trust your own history — and act on it with clarity.

This repository contains the source code for [librarymethod.com](https://librarymethod.com),
served via GitHub Pages and proxied through Cloudflare.

---

## Structure

```
librarymethod.com/
├── index.html                  ← Single-page site
├── assets/
│   └── images/
│       └── library-with-lot-books-shelves.jpg   ← Hero image (owner: GIGO Data, Inc.)
├── CNAME                       ← Custom domain for GitHub Pages
├── .gitignore
├── LICENSE                     ← All Rights Reserved
└── README.md
```

---

## Deployment

This site is deployed via **GitHub Pages** on the `main` branch.

Custom domain: `librarymethod.com`
DNS / CDN: Cloudflare

To deploy:
1. Push to `main`
2. GitHub Pages serves from root `/`
3. Cloudflare proxies `librarymethod.com` → GitHub Pages

---

## Assets & Favicon

Favicon and social preview image are served from `gigodata.com`:

- Favicon SVG:  `https://gigodata.com/favicon.svg`
- Favicon ICO:  `https://gigodata.com/favicon.ico`
- OG Preview:   `https://gigodata.com/preview.jpg`

---

## Image

The hero photograph (`library-with-lot-books-shelves.jpg`) was first published in
GIGO Data's LinkedIn Article 001 (February 1, 2026) and is the property of
GIGO Data, Inc. / Adrian Wise Santos.

**To add the image:** copy `library-with-lot-books-shelves.jpg` into `assets/images/`
and ensure the path in `index.html` matches:

```html
background-image: url('assets/images/library-with-lot-books-shelves.jpg');
```

---

## Legal

**Library Method™** is a trademark of **GIGO Data, Inc.**, a Delaware Corporation.

Copyright © 2026 GIGO Data, Inc. All Rights Reserved.

All intellectual property associated with the Library Method™ — including the name,
trademark, methodology, processes, and documentation — is the exclusive property of
GIGO Data, Inc. and is protected under U.S. and international IP laws and treaties.

See [LICENSE](./LICENSE) for full terms.

---

## Contact

- Web:    [gigodata.com](https://gigodata.com)
- Legal:  legal@gigodata.com
- X:      [@gigodata](https://x.com/gigodata)
