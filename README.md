# Abraham & Kurian – Chartered Accountants Website

Welcome to the source code for the **Abraham & Kurian** Chartered Accountants website. This repository contains a fully responsive, multi-page marketing site built in Webflow and exported as static assets.

---

## 📑 Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Getting Started](#getting-started)
5. [Deployment](#deployment)
6. [Folder Structure](#folder-structure)
7. [Contributing](#contributing)
8. [License](#license)

---

## Overview
Abraham & Kurian is a professional Chartered Accountancy firm offering tax, audit, and business advisory services. This website showcases our services, firm profile, client testimonials, and contact information, helping prospective clients connect with us easily.

## Features
• **Modern design** – Clean, corporate layout with professional typography and color palette.
• **Responsive** – Looks great on desktops, tablets, and mobiles.
• **Interactive elements** – Smooth scroll, reveal animations, and hover effects powered by Webflow interactions.
• **Service pages** – Dedicated sections for Taxation, Audit & Assurance, Compliance, and Advisory services.
• **Blog-ready** – Template sections for future articles or insights.
• **Contact form** – Collects enquiries which can be hooked to any backend (e.g., Formspree, Netlify Forms).

## Tech Stack
This is a purely front-end static site. No build tools are required.

| Layer | Details |
|-------|---------|
| Mark-up | HTML5 exported from Webflow |
| Styling | CSS3 (+ Webflow generated classes) |
| Interactivity | Webflow interactions + jQuery 3.5.1 |
| Fonts | Google Fonts – Montserrat, Inter, Source Code Pro |

> NOTE: Because the files are exported, updating styles or layout is best done inside Webflow and re-exporting.

## Getting Started
Clone the repository and open `index.html` in your browser, or serve it with a lightweight HTTP server:

```bash
# clone
git clone https://github.com/DualNova-Labs/abraham_and_kurian.git
cd abraham_and_kurian

# install a simple server if you don’t have one
npm i -g serve  # or use python -m http.server

# start the server on http://localhost:5000
serve -l 5000
```

## Deployment
The site can be hosted on any static hosting platform (GitHub Pages, Netlify, Vercel, AWS S3, etc.). Example: GitHub Pages

1. Push the `main` branch to GitHub (already set up).
2. In repository settings ➜ Pages, select branch `main` and folder `/` (root).
3. Save – GitHub will publish the site at `https://<username>.github.io/abraham_and_kurian`.

## Folder Structure
```
abraham_and_kurian/
├── css/          # Compiled Webflow CSS
├── fonts/        # Font files used by the template
├── images/       # Optimised images & icons
├── js/           # Webflow scripts + jQuery
├── index.html    # Landing page (Home V2)
└── README.md     # Project documentation (this file)
```

## Contributing
Improvements and bug-fixes are welcome! Please open an issue first to discuss changes. For major updates, fork the repo and submit a pull request.

## License
All code in this repository is released under the **MIT License**. The Webflow template assets (images, fonts, and design) are subject to their respective licenses.