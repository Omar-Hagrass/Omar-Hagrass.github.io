# Omar-Hagrass.github.io

Personal academic website. Plain HTML + CSS, no build step.

## Files
- `index.html` — Home / About
- `publications.html` — Publications
- `cv.html` — CV (links to full PDF)
- `teaching.html` — Teaching
- `style.css` — shared styling
- `profile.jpg` — your photo (see below)
- `profile.svg` — placeholder shown if `profile.jpg` is missing

## Add your photo
Drop a square headshot named `profile.jpg` into the repo root. Until you do,
a neutral placeholder is shown automatically. ~340×340px or larger works well.

## Deploy to GitHub Pages
1. Create a repository named exactly `Omar-Hagrass.github.io` (case-insensitive,
   but the username part must match your account).
2. Upload all files in this folder to the repository root (not in a subfolder).
3. In the repo: **Settings → Pages → Build and deployment**.
   Set **Source** = "Deploy from a branch", **Branch** = `main`, folder = `/ (root)`.
4. Wait ~1 minute. Your site goes live at:
   **https://omar-hagrass.github.io**

### Command-line alternative
```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/Omar-Hagrass/Omar-Hagrass.github.io.git
git push -u origin main
```
Then enable Pages in Settings as above.

## Editing
All content is plain HTML — edit the relevant `.html` file directly.
To add a publication, copy one `<li>...</li>` block in `publications.html`.
Colors and fonts live in the `:root` block at the top of `style.css`.

## Custom domain (optional)
If you later want e.g. `omarhagrass.com`, add a `CNAME` file containing the
domain and configure DNS — see GitHub Pages docs.
