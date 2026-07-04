# Smart Idima — Professional Portfolio

Static portfolio site for AIML-500 (Indiana Wesleyan University), ready to host on GitHub Pages.

## Files
- `index.html` — the whole site (bio, value proposition, skills, artifacts, resume, contact)
- `SMART_Idima_Resume.pdf` — **add this yourself** (copy your resume PDF into this folder with this exact name) so the Resume button works

## Before publishing — 2 quick edits in `index.html`
1. Replace every `YOUR-USERNAME` with your real GitHub username (2 spots: hero + contact).
2. In Artifact 02, replace the `href="#"` on "View the timeline" with your Lucid share link.

## Publish on GitHub Pages (personal site, cleanest URL)
```bash
# 1. Create a new repo on github.com named EXACTLY:  <username>.github.io
# 2. From this folder:
git remote add origin https://github.com/<username>/<username>.github.io.git
git branch -M main
git push -u origin main
```
Your site goes live at **https://<username>.github.io** within a minute or two.

### Alternative: any repo
Create any repo (e.g. `portfolio`), push these files, then in the repo:
**Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / root → Save.**
Live at `https://<username>.github.io/portfolio`.

## Updating later
Edit `index.html`, then:
```bash
git add -A && git commit -m "Update portfolio" && git push
```
