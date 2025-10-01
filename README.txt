# Churchill Power — Static Site (Starter)
This is a lightweight, static one-page site you can host anywhere (Hostinger, GitHub Pages, Netlify, Vercel).

## Files
- `index.html` — the page
- `styles.css` — styles
- `assets/logo.svg`, `assets/hero-bess.svg`, `assets/favicon.svg` — images

## Quick deploy to Hostinger (recommended if you already have hosting)
1. Log in to hPanel → Hosting → Files → **File Manager**.
2. Open **public_html** (or the root your domain points to).
3. Click **Upload** → upload the ZIP.
4. Select the ZIP → **Extract**. Make sure `index.html` ends up directly in `public_html/`.
5. In hPanel → **SSL** enable/activate **Let's Encrypt** for your domain and, if available, force HTTPS.
6. Visit `https://your-domain/`.

## Deploy to GitHub Pages (free)
1. Create a GitHub repo (public is fine).
2. Upload the files (index.html at the repo root).
3. Repo **Settings → Pages** → Deploy from **main** (root). Wait for Pages to build.
4. Add a **custom domain** (e.g., `www.churchillpower.ca`) in GitHub Pages settings.
5. In your DNS, add a CNAME: `www → your-username.github.io`. Optionally redirect apex to `www`.

## Deploy to Netlify (free)
1. Go to netlify.com → **New site from Git** or **Deploy manually** (drag & drop folder).
2. After the site is live on `*.netlify.app`, add your custom domain in Netlify.
3. In DNS, add CNAME: `www → yoursite.netlify.app`. Optionally set a redirect from apex to `www`.

## Deploy to Vercel (free)
1. vercel.com → **New Project** → Import repo or drag & drop.
2. Add your custom domain in Vercel.
3. Follow Vercel's DNS instructions (typically a CNAME for `www`).

## Contact form
The form uses Formspree. Replace `your_form_id` in `index.html` with your real endpoint.
Or remove the `<form>` and just use `mailto:info@churchillpower.ca`.

## Edit content
Open `index.html` and `styles.css` with any editor. No build step required.
