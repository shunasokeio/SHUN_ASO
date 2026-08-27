# Personal site

A single-page academic homepage. Edit `index.html` for content. Drop a headshot at `assets/photo.jpg` and a CV at `files/cv.pdf`.

## Host it for free (GitHub Pages)

This is what most CS students use. No ads, HTTPS included, custom domain optional.

1. Create a GitHub repo. For a clean URL, name it `YOUR_USERNAME.github.io` (site will be `https://YOUR_USERNAME.github.io`). Any other name works too (`https://YOUR_USERNAME.github.io/REPO`).
2. Push this folder:

```bash
git init
git add .
git commit -m "Initial personal site"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

3. On GitHub: **Settings → Pages → Build and deployment**.
   - Source: **Deploy from a branch**
   - Branch: `main` / `/ (root)`
4. Wait a minute. The Pages settings screen will show the live URL.

Later edits: change a file, commit, push. The site updates in a minute or two.

### Custom domain (optional)

Buy a domain (~$10/year). In the repo add a `CNAME` file containing `yourname.com`, then point the domain's DNS to GitHub Pages ([docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)).

## Other free hosts

Same files work on [Cloudflare Pages](https://pages.cloudflare.com/) or [Netlify](https://www.netlify.com/) if you prefer a drag-and-drop deploy. GitHub Pages is the usual choice for this kind of site.
