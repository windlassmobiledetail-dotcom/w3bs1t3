# Windlass Mobile Detailing — Website

The website for Windlass Mobile Detailing, ready to publish on GitHub Pages.

## What's in this folder

- `index.html` — the homepage (loads automatically at your site's root)
- `404.html` — a branded "page not found" page
- `.nojekyll` — tells GitHub Pages to serve the files as-is (skip Jekyll processing)
- `README.md` — this file

Everything is self-contained. There are no other files to upload.

## How to publish on GitHub Pages

1. Go to https://github.com and sign in (create a free account if you don't have one).
2. Click the **+** in the top right, then **New repository**.
3. Name it (for example, `windlass-site`), set it to **Public**, and click **Create repository**.
4. On the new repository page, click **uploading an existing file**.
5. Drag in the contents of this folder: `index.html`, `404.html`, and `.nojekyll`.
   (If GitHub hides `.nojekyll`, it's fine — it's optional. `index.html` is the essential one.)
6. Click **Commit changes**.
7. Go to **Settings** → **Pages** (in the left sidebar).
8. Under **Branch**, choose `main`, keep the folder as `/ (root)`, and click **Save**.
9. Wait 1–2 minutes. GitHub will show a link like
   `https://YOUR-USERNAME.github.io/windlass-site/` — that's your live site.

## Using your own domain (optional)

If you buy a domain later (e.g. `windlassdetailing.com`):

1. In **Settings** → **Pages**, enter the domain under **Custom domain** and save.
2. At your domain registrar, point the domain to GitHub Pages following
   GitHub's instructions: https://docs.github.com/pages/configuring-a-custom-domain-for-your-github-pages-site

## Updating the site later

Edit `index.html` (or replace it), upload the new version to the same repository,
and commit. Your live site updates automatically within a minute or two.
