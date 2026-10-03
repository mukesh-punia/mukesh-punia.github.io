# Mukesh Kumar — Academic website

A lightweight, five-page website prepared for GitHub Pages. No build service, plugins, or paid hosting are required.

## Publish

1. Sign in to the GitHub account `mukesh-punia`.
2. Create a **public** repository named exactly `mukesh-punia.github.io`.
3. Upload the contents of this folder to the repository root. `index.html` must be at the root, beside `research.html`, `teaching.html`, `cv.html`, and `contact.html`. Keep the `assets` folder intact. Upload the extracted files, not the ZIP itself.
4. In repository Settings → Pages, choose **Deploy from a branch**, then **main** and **/(root)**, and save.
5. Once deployment succeeds, the site will be at https://mukesh-punia.github.io/ .

## Edit

The website is ordinary HTML and CSS. Edit page text directly in GitHub using the pencil icon and commit the change; GitHub Pages will publish the update.

- `index.html`: introduction, biography, selected publications.
- `research.html`: publication entries, summaries, chapters, letters, ongoing work, and public writing. Duplicate an existing `<article class="paper">` block to add a publication. Update selected publications on `index.html` separately.
- `teaching.html`: teaching experience and resources link.
- `cv.html`: education, appointments, and the public Google Drive CV link.
- `contact.html`: email and professional profiles.
- `assets/style.css`: shared colours, fonts, and responsive layout.
- `assets/portrait.jpg`: existing portrait from the Google Site.
- `publications.json`: an editable reference copy of publication data; changing it alone does not update the HTML pages.

The CV stays at its existing public Google Drive URL. No Google Drive editing access is needed. The site links to your Google Sites resources page while that collection remains there. Google Fonts are optional; local serif and sans-serif fallback fonts are provided.

## Content review notes

Content was transferred from https://sites.google.com/view/mukesh-punia and its embedded public CV on 3 October 2026. Research summaries were shortened and are labelled as summaries, not verbatim abstracts.

The CV has newer ongoing-research titles/statuses than the research page; this version uses the CV entries. Please confirm these before final publication. The Economics of Infrastructure-II teaching year differs between the website (Spring 2018) and CV (2017); the year is omitted pending clarification. No new credentials or research results have been invented.

Only public website material belongs in this repository. The old Google Site has not been changed.
