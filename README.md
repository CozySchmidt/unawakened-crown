# The Unawakened Crown — documentation site

One-page static site for the IAT 210 Board Game Preproduction Prototype submission.
Everything is in `index.html` (inline CSS/JS) + `assets/`. No build step.

## Preview locally

```powershell
cd unawakened-crown-website
python -m http.server 8080
# open http://localhost:8080
```

## Deploy to GitHub Pages

1. Create a new **public** repo on GitHub (e.g. `unawakened-crown`).
2. In this folder:
   ```powershell
   git init
   git add .
   git commit -m "Unawakened Crown documentation site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/unawakened-crown.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Source: Deploy from a branch → main / (root) → Save**.
4. After ~1 minute the site is live at `https://<your-username>.github.io/unawakened-crown/` — that's the URL you submit to Canvas.

## Before submitting

Open `index.html` and work through the `TODO:` checklist in the comment block at
the top (board screenshot, trailer embed, the four PDFs, meeting dates, team names,
copy review). Every placeholder is visibly tagged on the page so nothing gets missed.
