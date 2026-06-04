# Charles Allison Jr. — Portfolio

A minimal, Apple-inspired Biology & Biotechnology portfolio built for GitHub Pages.

## File Structure

```
/
├── index.html                          ← The entire site (all pages)
├── Charles_Allison_Resume.pdf          ← Your resume (add this file)
├── Environmental_Data_Analysis_Report.pptx  ← Your PPTX (add this file)
└── README.md
```

## Setup for GitHub Pages

1. **Create a new GitHub repository** named `CharlesAllison.github.io`
   (this makes it your root GitHub Pages site at `https://charlesallison.github.io`)

   Or name it anything (e.g. `portfolio`) — it'll live at `https://charlesallison.github.io/portfolio`

2. **Upload these files** to the repository:
   - `index.html`
   - `Charles_Allison_Resume.pdf` ← rename your resume PDF to this exact filename
   - `Environmental_Data_Analysis_Report.pptx` ← your uploaded PPTX file

3. **Enable GitHub Pages**:
   - Go to your repo → Settings → Pages
   - Source: Deploy from a branch → `main` → `/ (root)`
   - Click Save

4. Your site will be live in ~1 minute at the URL shown.

## Adding Your Resume PDF

Rename your resume PDF to exactly:
```
Charles_Allison_Resume.pdf
```
and place it in the root of the repository. The "Download Résumé" buttons will link to it automatically.

## Pages Included

- **Home** — Hero landing with CTA buttons
- **About** — Bio, skills chips, and personal details
- **Projects** — All 4 lab/research projects with detail pages
- **Experience** — Marketing Assistant role, certifications, awards
- **Contact** — Email, LinkedIn, GitHub, phone

## Customization Tips

- To add a new project: duplicate one of the `project-card` divs in the Projects page and add a corresponding `page-proj-*` div
- All styles are in the `<style>` block at the top of `index.html`
- Colors are controlled by CSS variables at `:root` — change `--accent` to update the green theme
