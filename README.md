# Library Method™ — librarymethod.com

> **Know your story. Trust your data. Act with clarity.**

The official public website for **Library Method™**, a proprietary methodology **created and owned by Adrian Wise Santos** and **operated by GIGO Data, Inc. under exclusive licence**.

---

# About

**Library Method™** is a structured, human-aware methodology for capturing, classifying, verifying, and retrieving work history as defensible evidence.

It is designed for professionals, teams, and organisations that require reliable records, clear provenance, and trustworthy historical data — especially in environments involving governance, compliance, and AI systems.

This repository contains the source code for **https://www.librarymethod.com**, deployed via **GitHub Pages** and proxied through **Cloudflare**.

---

# Repository Structure

```
librarymethod.com/
├── index.html
├── licence.html
├── ai-policy.html
├── assets/
│   ├── brand/
│   ├── fonts/
│   ├── icons/
│   └── images/
│       └── librarymethod_hero_v1_2026_02_01.jpg
├── metadata/
├── opengraph/
├── favicon.ico
├── CNAME
├── .gitignore
├── .nojekyll
├── LICENSE
└── README.md
```

---

# Deployment

The site is deployed automatically using **GitHub Pages**.

**Deployment pipeline**

1. Push changes to the `main` branch
2. GitHub Pages serves the repository root (`/`)
3. Cloudflare proxies traffic to GitHub Pages

**Domain configuration**

Custom domain:

```
librarymethod.com
```

DNS / CDN:

```
Cloudflare
```

---

# Assets

Primary site assets are stored in the repository.

Hero image:

```
assets/images/librarymethod_hero_v1_2026_02_01.jpg
```

The hero photograph was originally published in **GIGO Data LinkedIn Article 001 (February 1, 2026)** and is owned by **Adrian Wise Santos / GIGO Data, Inc.**

Ensure the path in `index.html` matches:

```css
background-image: url('assets/images/librarymethod_hero_v1_2026_02_01.jpg');
```

---

# Open Graph & Favicon

Social preview and favicon resources may be served from **gigodata.com**.

Examples:

```
https://www.gigodata.com/favicon.ico
https://www.gigodata.com/favicon.svg
```

OpenGraph preview image:

```
opengraph/librarymethod_og_1200x630_v1_2026_02_01.png
```

---

# Legal

**Library Method™** is the intellectual property of **Adrian Wise Santos**.

**GIGO Data, Inc.**, a Delaware corporation, operates and deploys **Library Method™ under exclusive licence** from the intellectual property owner.

Copyright © 2026 Adrian Wise Santos.
All rights reserved.

See:

```
LICENSE
```

for repository licensing terms.

Public rights notice:

```
https://www.librarymethod.com/licence.html
```

---

# Contact

Security:

```
security@gigodata.com
```

Web:

```
https://www.gigodata.com
```

X:

```
https://x.com/gigodata
```
