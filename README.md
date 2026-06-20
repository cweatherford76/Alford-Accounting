Personal budgeting and professional bookkeeping site for Alford Accounting, a woman-owned accounting business founded by Joanne Alford.

**Live site:** _add your GitHub Pages URL here once deployed_

## Pages

- `index.html` — Home
- `about.html` — About Joanne
- `services.html` — Services
- `testimonials.html` — Testimonials
- `contact.html` — Contact

## Stack

Static site — plain HTML, CSS, and vanilla JavaScript. No build step, no framework, no dependencies to install.

- **Fonts:** Playfair Display (headings) and Inter (body), loaded from Google Fonts
- **Brand colors:** deep teal `#124e5a`, olive gold `#6a765d`, parchment cream `#fafaf7`

## Project structure

```
alford-accounting/
├── index.html
├── about.html
├── services.html
├── testimonials.html
├── contact.html
├── styles.css
├── app.js
└── images/
    ├── logo-mark.png     # AA monogram, used in the nav
    ├── logo-seal.png      # full circular seal, used in the footer
    └── joanne.jpg         # photo on the About page
```

All five HTML pages share `styles.css` and `app.js`. Keep the `images` folder in place alongside the HTML files — the pages reference it as a relative path (`images/logo-mark.png`, etc.), so the folder name and structure must stay intact.

## Running locally

No build tools or server required. Clone the repo and open any HTML file directly in a browser:

```
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
open index.html
```

(Or just double-click `index.html` in Finder/Explorer.)

## Deploying with GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select the `main` branch and `/ (root)` folder
4. Save — your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO/` within a minute or two

## Editing

- **Content:** edit the relevant HTML file directly
- **Styling:** all shared styles live in `styles.css`
- **Interactivity** (mobile nav toggle, scroll reveal animations, contact form): `app.js`
- **Images:** replace files in `images/` directly, keeping the same filenames, or update the `src` paths in the HTML if you rename them

### Known placeholder content

The testimonials on `testimonials.html` are sample quotes marked with `[Client name]` — replace these with real client testimonials (with their permission) before publishing.
