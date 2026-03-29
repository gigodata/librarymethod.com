# Library Method™ — librarymethod.com

Know your story. Trust your data. Act with clarity.

The official public website for **Library Method™**, a proprietary methodology created and owned by **Adrian Wise Santos** and operated by **GIGO Data, Inc. under exclusive licence**.

---

# About

**Library Method™** is a structured, human-aware methodology for capturing, classifying, verifying, and retrieving work history as defensible evidence.

It is designed for professionals, teams, and organisations that require reliable records, clear provenance, and trustworthy historical data — especially in environments involving governance, compliance, and AI systems.

This repository contains the source code for:

https://www.librarymethod.com

The site is deployed using **GitHub Pages** and proxied through **Cloudflare**.

---

# Repository Structure

```
librarymethod.com/
├── index.html
├── robots.txt
├── sitemap.xml
├── llms.txt
├── favicon.ico
├── CNAME
├── .gitignore
├── .nojekyll
├── LICENSE
├── LIBRARY-METHOD.md
├── README.md
│
├── assets/
│   ├── brand/
│   ├── fonts/
│   ├── icons/
│   └── images/
│       └── librarymethod_hero_v1_2026_02_01.jpg
│
├── css/
│
├── js/
│   ├── accessibility_js/
│   ├── analytics_js/
│   └── ui_behaviours_js/
│
├── language/
│
├── legal/
│   ├── index.html
│   ├── acceptable-use.html
│   ├── ai-policy.html
│   ├── collection-policy.html
│   ├── data-processing.html
│   ├── legal.css
│   ├── licence.html
│   ├── privacy.html
│   └── terms.html
│
├── metadata/
│
└── opengraph/
    └── librarymethod_og_1200x630_v1_2026_02_01.png
```

---

# Deployment

The site is deployed automatically using **GitHub Pages**.

Deployment pipeline:

1. Changes are pushed to the `main` branch
2. GitHub Pages builds and serves the repository root (`/`)
3. Cloudflare provides DNS, TLS, caching, and edge proxying

Domain configuration:

librarymethod.com

DNS / CDN provider:

Cloudflare

---

# Assets

Primary site assets are stored in the repository.

Hero image:

assets/images/librarymethod_hero_v1_2026_02_01.jpg

The hero photograph was originally published in **GIGO Data LinkedIn Article 001 (February 1, 2026)** and is owned by **Adrian Wise Santos**.

Ensure the path in `index.html` matches:

background-image: url('assets/images/librarymethod_hero_v1_2026_02_01.jpg');

---

# Open Graph & Favicon

Social preview and favicon resources may be served from **gigodata.com**.

Examples:

https://www.gigodata.com/favicon.ico
https://www.gigodata.com/favicon.svg

OpenGraph preview image:

opengraph/librarymethod_og_1200x630_v1_2026_02_01.png

---

# Crawl Policy

The **Library Method™ website is intentionally open to search engine and research crawlers**.

robots.txt allows full indexing to support:

• public research
• archival preservation
• academic citation
• search indexing

AI usage is governed by the AI & Data Policy:

https://www.librarymethod.com/legal/ai-policy.html

---

## AI & Machine-Readable Policy

This repository includes machine-readable documentation intended for search engines,
research crawlers, and AI systems.

Files provided:

• `robots.txt` — search crawler policy
• `sitemap.xml` — canonical site map
• `llms.txt` — structured description of the Library Method™ concept
• `legal/ai-policy.html` — policy governing AI usage and restrictions

These files establish a machine-readable layer that enables:

• correct attribution
• structured ingestion by AI systems
• preservation of provenance
• enforcement of usage and licensing constraints

This ensures Library Method™ is not only discoverable,
but correctly interpreted and governed across AI systems.

---

# Legal

**Library Method™** is the intellectual property of **Adrian Wise Santos**.

**GIGO Data, Inc.**, a Delaware corporation incorporated **June 24, 2025**, operates and deploys **Library Method™ under exclusive licence** from the intellectual property owner.

Library Method™ was first publicly published **February 1, 2026**.

Jurisdiction:

United States (Delaware), European Union (EU), and Brasil (BR)

Applicable data protection frameworks:

• GDPR (General Data Protection Regulation — European Union)
• LGPD (Lei Geral de Proteção de Dados — Brasil)

Copyright © 2026 Adrian Wise Santos.
All rights reserved.

Repository licensing terms are defined in:

LICENSE

Public rights notice:

https://www.librarymethod.com/legal/licence.html

---

# Intellectual Property Notice

Library Method™ is a proprietary methodology created by **Adrian Wise Santos**.

The methodology, naming, structure, and associated materials are protected intellectual property.

**GIGO Data, Inc.** operates Library Method™ under exclusive licence from the intellectual property owner.

No licence is granted for reproduction, derivative implementation, or system replication without explicit written permission.

---

# Epistemic Position

Library Method™ operates on a simple premise:

What cannot be traced cannot be trusted.
What cannot be trusted cannot scale.

This repository is not only a website.
It is a structured, verifiable, machine-readable assertion of:

• authorship
• provenance
• methodology
• governance

It is designed to be ingested by both humans and AI systems
as a canonical reference.

---

# Contact

Security:
[security@gigodata.com](mailto:security@gigodata.com)

Web:
https://www.gigodata.com

X:
https://x.com/gigodata
