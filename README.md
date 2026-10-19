# CloudBlitz XDSAAI Placement Training Portal

A standalone static portal for the 12-day XDSAAI placement training pathway. This repository is independent of the CDEC portal.

## Included modules

- Dashboard and 12-day syllabus
- Day 1–5 placement readiness
- Day 6–9 project sprint
- Day 10 project review question bank and trainer rubric
- Day 11–12 professional communication and mock-interview readiness
- Resume workshop
- Naukri / LinkedIn profile checklist
- Documents and placement guidelines
- Placement-readiness checklist
- Trainer Mode with previous/next navigation
- Search, dark theme, mobile navigation, print-friendly layout
- Browser-local progress tracking

## Publish with GitHub Pages

The workflow at `.github/workflows/pages.yml` deploys the repository root directly to GitHub Pages on pushes to `main`.

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. Push a commit to `main`, or open **Actions** and run **Deploy CloudBlitz XDSAAI Portal to GitHub Pages**.
4. When the workflow finishes successfully, the site URL will be:
   `https://abhilashmwaghmare.github.io/XDSAAI-Placement-Training-Portal/`

No Cloudflare Pages is used.

## Progress and privacy note

Completion and checklist states are stored in the current browser using localStorage. They do not sync between devices or users and are not visible to trainers remotely. Do not store sensitive personal information in this static site.

The readiness percentage is a checklist completion indicator, not a placement guarantee or independently verified skills assessment.

## Customization

- Edit `index.html` for the static page shell.
- Edit `assets/styles.css` for visual styles.
- Edit `app.js` for syllabus topics, question bank and interactions.

Use genuine student project details and verified achievements only. Confirm any batch-specific document requirements with the placement team.
