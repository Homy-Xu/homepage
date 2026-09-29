# GitBook Setup Guide

This folder is a ready-to-use single-page academic homepage draft modeled after the concise, research-first structure of Xuanhe Zhou's GitBook homepage.

## Recommended publishing route: GitHub + GitBook Git Sync

1. Create a GitHub repository, for example: `Homy-Xu/homepage`.
2. Upload the contents of this folder to the repository root:
   - `README.md`
   - `SUMMARY.md`
   - `assets/CV_Homy_Xu.pdf`
3. In GitBook, create a new Docs Site / Space.
4. Choose **Git Sync** and connect the GitHub repository.
5. Use the `main` branch.
6. Preview the site, then publish it as a public site.
7. Set the site title to **Homy Xu**.

GitBook supports Markdown and two-way Git Sync with GitHub, so later updates can be made either in GitBook's visual editor or directly in the repository.

## Alternative: direct import

GitBook supports Markdown import. You can import `README.md` directly. If the relative CV attachment does not survive the import, upload `CV_Homy_Xu.pdf` through GitBook's Files/Library panel and replace the CV link at the top of the page with the uploaded file link.

## Before publishing

- **English-name consistency:** the CV title currently uses **Homy Xu**, while the public paper author lists use **Hongming Xu**. Choose one consistent academic display style before sending the homepage to faculty. A clean option is `Hongming (Homy) Xu`.
- Add a **Google Scholar** link once the profile is ready.
- Add an **ORCID** link if you use one.
- Add a professional **headshot** only if you want one; it is not required.
- Add project figures only when they improve understanding. One overview figure per major project is enough.
- The phone number from the CV is intentionally omitted from the public homepage.
- Keep publication status accurate as papers move from under review to accepted/published.
- For the QCDKM paper, add a public paper/project URL only after you have a verified link.

## Suggested GitBook visual settings

- Theme: Light
- Layout: clean/default
- Site title: `Homy Xu`
- Homepage: `README.md`
- Keep the page single-column and research-first
- Avoid excessive cards, animations, or decorative sections
- Keep `Selected Research` more prominent than `Skills`

## Suggested future additions

When available, add:
- Google Scholar
- ORCID
- Research group/lab affiliation
- Project overview figures
- Stable paper/project links
- A short `Research Experience` section if you want to expose internships or lab roles publicly
