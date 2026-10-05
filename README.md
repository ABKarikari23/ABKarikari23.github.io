# ABKarikari23.github.io

Personal portfolio of **Abraham Nana Kofi Karikari** — Python developer and AI engineer, author of the *AI Agents with Python 2026* series.

Built with plain HTML, CSS, and JavaScript. No frameworks, no build step.

## Live site

<https://abkarikari23.github.io>

This repo is a GitHub **user site**: because it is named `ABKarikari23.github.io`, GitHub Pages automatically serves the repository root from the default branch. No extra Pages configuration is required.

## Local development

Open `index.html` directly in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then open <http://127.0.0.1:8000>.

## Editing

- **Content** — all in [index.html](index.html); each section is clearly commented (`About`, `Projects`, `Skills`, `Writing`, `Resume`, `Contact`).
- **Styling** — colors and spacing live as CSS custom properties at the top of [styles.css](styles.css) (`--gold`, `--bg`, etc.).
- **Resume** — drop your CV into the repo root as `resume.pdf`; the Download CV button links to it.

## Custom domain (optional)

To serve this site at a custom domain (e.g. `abkarikari23.tech`):

1. Add a file named `CNAME` containing just the domain: `abkarikari23.tech`
2. Point the domain's DNS at GitHub Pages (A records to GitHub's IPs, or a CNAME record to `abkarikari23.github.io`)
3. Enable HTTPS in the repo's **Settings → Pages**.
