# Ski Gear Transport Survey

This is a single-file static survey site for a ski bag product concept.

## Deploy recommendation
- Best default: **Vercel**
- Alternatives: **Netlify**, **GitHub Pages**

## Before deploy
1. Create a free form endpoint in Formspree.
2. Replace this in `index.html`:

```html
<form action="https://formspree.io/f/REPLACE_WITH_YOUR_FORM_ID" method="POST">
```

with your real Formspree endpoint.

## Deploy to Vercel
### Option A: GitHub import
1. Push this folder to a GitHub repo.
2. In Vercel, import the repo.
3. Framework preset: `Other` or `No framework`.
4. No build command needed.
5. Output directory: leave empty.
6. Deploy.

### Option B: CLI
```bash
npm i -g vercel
vercel --prod
```

## Deploy to Netlify
1. Push to GitHub.
2. Import repo into Netlify.
3. Build command: leave empty.
4. Publish directory: `.`

## Deploy to GitHub Pages
Because this is a static HTML file, GitHub Pages can publish it directly from the repository root or `/docs` folder.
