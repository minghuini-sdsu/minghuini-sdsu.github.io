# Minghui Ni — Personal Website (GitHub Pages)

Static migration of https://minghui-ni.squarespace.com to free GitHub Pages hosting.

## Structure

- `index.html` — Home / bio
- `research.html` — Research lines
- `publications.html` — Publications
- `teaching.html` — Teaching experience
- `cv.html` — CV download page
- `styles.css` — Site stylesheet
- `assets/` — Images and CV PDF
  - `profile.jpg` — headshot
  - `research-bivalence.png` — research illustration 1
  - `research-bias.jpg` — research illustration 2
  - `cv.pdf` — full CV

## Deploy to GitHub Pages (free)

1. Create a GitHub account at https://github.com (if you don't have one).
2. Create a **new public repository** named `<username>.github.io` (replace `<username>` with your GitHub username). This special name makes the site live at `https://<username>.github.io`.
3. Upload all files in this folder to the repository (drag-and-drop on github.com works, or `git push`).
4. Go to the repo's **Settings → Pages** and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
5. After a minute or two, the site is live at `https://<username>.github.io` — free, no Squarespace subscription needed.

## Custom domain (optional, ~$12/year)

If you own a domain (e.g. `minghuini.com`):
1. Add a file named `CNAME` (no extension) in the repo root containing just the domain name.
2. At your domain registrar, add DNS records: an `A` record pointing to GitHub Pages IPs (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153), or a `CNAME` record pointing to `<username>.github.io`.
3. In repo Settings → Pages, enter the custom domain and enforce HTTPS.

## Updating content later

Edit the HTML files and push — GitHub Pages rebuilds automatically in ~1 minute. No build step, no dependencies.
