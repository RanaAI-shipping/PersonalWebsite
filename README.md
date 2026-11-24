# PersonalWebsite

Personal website of Aaquib Al Hossain, product leader in fintech.

A single static page (`index.html` + `styles.css`) with no build step and no dependencies. It supports light and dark mode and works at phone widths.

## Sections

1. **Hero:** positioning statement and calls to action
2. **Proof bar:** headline metrics and companies
3. **Case studies:** problem, decision and outcome for six projects
4. **How I lead:** operating principles
5. **Built by me:** side projects and published code
6. **Experience and education**
7. **Contact**

## Content rules

This repo is **public**. Facts come from the master resume in the private `ResumePrep` repo. Never add:

- compensation, bonus or rating details
- internal feedback, vendor negotiations or unreleased initiatives
- phone numbers or other private contact details
- any metric still marked ⚠️ (unresolved) in `ResumePrep/source/achievements.md`

## Preview locally

Open `index.html` in a browser, or run:

```sh
python3 -m http.server 8000
```

## Deploy

Pick one:

- **GitHub Pages:** Settings → Pages → Deploy from branch → choose `main` and the `/ (root)` folder.
- **Netlify or Vercel:** import the repo. No build command, publish directory `/`.

Then point a custom domain at it and use that URL on LinkedIn and your resume.
