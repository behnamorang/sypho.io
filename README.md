# sypho.io — Static Site

Standalone static website (HTML/CSS/JS) hosted on Hostinger shared hosting.

**This repo is fully independent** — no connection to the `Sypho.co.uk` (Next.js dispatch platform)
or `Sypho CRM` codebases/repos. Do not merge or share dependencies with those projects.

## Structure

- `index.html` — main landing page
- `clinic.html` — clinic-related page
- `Sypho-Lead.dc.html` / `Sypho-Med.dc.html` / `Sypho-Trade.dc.html` — sub-brand pages
- `support.js` — shared JS logic
- `assets/` — logos and static images

## Deployment

This is a static site with no build step. Deployment target: Hostinger shared hosting via FTP/SFTP.

Workflow:
1. Edit locally or via Cursor (connected to this repo)
2. Commit + push to `main`
3. Deploy to Hostinger (manual upload for now; GitHub Actions FTP deploy can be added later)

## Planned work

- Add cinematic scroll effects (GSAP + ScrollTrigger, scroll-linked video scrubbing, parallax)
