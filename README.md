# Kokul Prasanth Anand — Portfolio Website

A personal portfolio website for Kokul Prasanth Anand, B.E. Computer Science & Engineering student at Anand Institute of Higher Technology (2025–2029).

**Live site:** _add your live link here after deploying (see below)_

## About

This is a single-page portfolio site built to introduce who I am, what I'm learning, and how to get in touch — the kind of page a recruiter or collaborator can look at before reaching out.

Sections: Home · About · Skills · Resume · Contact

## Tech stack

- HTML5
- CSS3 (no framework — hand-written, custom design system)
- Vanilla JavaScript (scroll reveal animation, animated canvas background, print-to-PDF)

This project is **100% frontend** — there is no backend, server, database, or API of any kind. It's a static site that runs entirely in the browser, so it can be hosted for free on any static hosting platform.

## Project structure

```
portfolio-repo/
├── index.html          # all markup + embedded CSS + JS
├── assets/
│   └── profile.png     # profile photo used in the hero section
└── README.md
```

## Features

- Responsive layout (mobile, tablet, desktop)
- Animated node/constellation background in the hero section
- Scroll-triggered section reveals (disabled automatically if the visitor has "reduce motion" turned on)
- One-click **Save as PDF** on the Resume section (uses the browser's native print function — no backend needed)
- Direct contact details (phone, email, LinkedIn) with click-to-call and click-to-email links

## Setup (run locally)

No build tools or dependencies required.

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```
2. Open `index.html` directly in your browser — or, for the best experience with live reload, serve it locally:
   ```bash
   # Python 3
   python -m http.server 8000
   # then visit http://localhost:8000
   ```

## Deployment

### Option A — GitHub Pages (recommended, free)

1. Push this project to a public GitHub repository.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Choose the `main` branch and `/ (root)` folder, then click **Save**.
5. GitHub will publish the site at:
   ```
   https://<your-username>.github.io/<your-repo-name>/
   ```
   It can take a minute or two to go live.

### Option B — Netlify (drag and drop, free)

1. Go to [app.netlify.com/drop](https://app.netlify.com/drop).
2. Drag the whole `portfolio-repo` folder onto the page.
3. Netlify gives you a live URL immediately, with an option to add a custom domain later.

### Option C — Vercel

1. Go to [vercel.com/new](https://vercel.com/new) and import the GitHub repository.
2. Leave the default settings (no framework/build step needed) and deploy.

## Updating content

All content lives in `index.html`. To update text, edit the relevant section directly — each section is clearly commented (`<!-- HOME -->`, `<!-- ABOUT -->`, etc.). To swap the profile photo, replace `assets/profile.png` with a new image of the same filename, or update the `src` in the `<img>` tag under the Home section.

## Contact

- Phone: +91 94439 66652
- Email: kokulanand7@gmail.com
- LinkedIn: [kokul-prasanth-anand](https://www.linkedin.com/in/kokul-prasanth-anand-21120a361)
