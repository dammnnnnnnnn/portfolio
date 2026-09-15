# Adam Roslan — portfolio

Static site. No build step, no dependencies.

    index.html      the whole page (CSS + JS inline)
    assets/         photos, project covers, slide images, clips, PDFs
    vercel.json     cache headers

## Put it online

**GitHub + Vercel (recommended, redeploys on every push)**

1. Create an empty repo on GitHub, e.g. `portfolio`.
2. In this folder:

        git init
        git add .
        git commit -m "portfolio"
        git branch -M main
        git remote add origin https://github.com/dammnnnnnnnn/portfolio.git
        git push -u origin main

3. On vercel.com choose Add New > Project, import the repo, and deploy.
   Framework preset: Other. Build command: none. Output directory: leave blank.

**Drag and drop (fastest, no git)**

Zip this folder and drop the zip on vercel.com/new — Vercel serves it as a static site.

## Editing

Everything lives in `index.html`. Swap a photo by replacing the file in `assets/`
and keeping the same filename.
