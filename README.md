# bluefrog Plumbing + Drain of West Houston

Custom landing page and marketing website for a premium plumbing and drain service brand serving West Houston and surrounding communities.

## Overview

This project is a modern static website built to showcase:
- 24/7 emergency plumbing service
- trustworthy local service and professionalism
- premium conversion-focused call-to-action design
- service area visibility and customer trust messaging

The site is designed to feel clean, premium, and locally credible while still being easy to deploy to GitHub and Vercel.

---

## Local Preview

Run the site locally with:

```bash
npm install
npm start
```

Then open:
- http://localhost:3000

---

## Project Structure

```bash
bluefrog-plumbing/
├── index.html              # Main landing page
├── DESIGN.md               # Brand and UI design system documentation
├── README.md               # Project overview and setup guide
├── package.json            # Local preview script and dependencies
├── vercel.json             # Vercel deployment config
├── .gitignore              # Git ignore rules
├── images/                 # Brand and campaign assets
├── variants/               # Alternate page layouts and concepts
├── design-system.json       # Design tokens and styling source
├── project-manifest.json    # Project manifest metadata
└── node_modules/           # Installed dependencies
```

---

## Tech Stack

- HTML5
- Tailwind CSS via CDN
- Vanilla JavaScript for interactions and scroll effects
- Static hosting ready for Vercel

---

## Deployment

This site is ready to deploy as a static website.

### GitHub

```bash
git init
git add .
git commit -m "Initial website launch"
git branch -M main
git remote add origin <your-github-repo-url>
git push -u origin main
```

### Vercel

1. Import the GitHub repository in Vercel.
2. Use the project root as the root directory.
3. Keep the build command empty for a static site.
4. Deploy.

---

## Brand Direction

The site emphasizes:
- trust and reliability
- fast emergency response
- modern but approachable service design
- mobile-first CTA conversion

---

## Notes

This repository is intentionally kept lightweight and static so it can be hosted easily on Vercel without a framework build step.
