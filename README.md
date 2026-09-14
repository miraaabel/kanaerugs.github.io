# ORÍKÌ Studio — Website

A one-page placeholder site for an African fashion brand, ready to publish free on GitHub Pages.

## What's here
- `index.html` — the entire site (structure, styling, and a tiny bit of JS all in one file)
- No build step, no dependencies to install — just HTML/CSS/JS plus Google Fonts

Everything you see (brand name, product names, prices, bio, contact details, and the colored pattern blocks standing in for photos) is placeholder content. Search the file for the word "placeholder" to find every spot to replace.

## Publish it on GitHub Pages (free hosting)

1. **Create a repository**
   Go to github.com → New repository → name it something like `oriki-site` → keep it Public → Create.

2. **Upload the files**
   On the repository page, click "Add file" → "Upload files", then drag in `index.html` and `README.md`. Commit the changes.

3. **Turn on Pages**
   Go to the repo's **Settings** tab → **Pages** (left sidebar) → under "Build and deployment", set Source to **Deploy from a branch** → Branch: `main`, folder `/ (root)` → Save.

4. **Visit your site**
   GitHub will show a URL like `https://yourusername.github.io/oriki-site/` — it can take a minute or two to go live the first time.

## Making changes later
Any time you edit `index.html` (in GitHub's web editor, or on your computer with `git push`), the live site updates automatically within a minute of the change reaching the `main` branch.

## Before you launch for real
- Replace the brand name, tagline, and copy throughout
- Swap the colored pattern blocks for real product photography (same size/shape works best)
- Replace WhatsApp, email, Instagram, and address details in the Contact section
- Connect the contact form to a real inbox — the easiest no-backend options are [Formspree](https://formspree.io) or [Netlify Forms](https://docs.netlify.com/forms/setup/); either just needs a small change to the `<form>` tag
- Consider a custom domain (Settings → Pages → Custom domain) once you have one
