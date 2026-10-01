# Ting Xu – personal website

The website is made of three files:

- `index.html` is the whole page.
- `photo.jpg` is your portrait.
- `.nojekyll` is an empty file that makes GitHub serve the page exactly as written. It is hidden on a Mac; press Cmd+Shift+. in Finder to see it.

## Publish on GitHub Pages (once, about 10 minutes, free)

1. Create an account at https://github.com. Your username becomes part of your web address, so pick it with care (for example `tingxu-research`).
2. Click **+ → New repository**. Name it exactly `<your-username>.github.io`, choose **Public**, and click **Create repository**.
3. Click **uploading an existing file**. Drag in `index.html`, `photo.jpg` and `.nojekyll`, then click **Commit changes**.
4. Go to **Settings → Pages**. Under "Branch", choose `main` and `/ (root)`, then click **Save**.
5. After 1–2 minutes your site is live at `https://<your-username>.github.io`.

## Editing later (in your web browser)

1. Open your repository on github.com and click `index.html`.
2. Click the **pencil icon**.
3. Press Cmd+F to find the text you want to change, then edit it.
4. Click **Commit changes**. The live site updates in about a minute.

If something breaks, open the file's **History** on GitHub to see and restore any earlier version.

## Common edits

**Add a new paper.** Search for `<ol class="pubs"`. Copy one whole block from `<li class="pub"` to its closing `</li>`, then paste it just below `<ol class="pubs" id="pubs">` so it appears first. Change the year, title, authors, journal and DOI link (the DOI appears in 2 places).

**Add a talk, job or award.** Copy one `<li class="row">…</li>` line in that section and edit it.

**Change your photo.** Upload a new picture with the same name, `photo.jpg`. A portrait shape works best (4:5, about 640 × 800 pixels).

**Special characters.** Typing curly quotes, dashes or accents directly is fine when you edit on github.com.

## After it is live

- Add the link to your email signature, your CV, your Google Scholar and ORCID profiles, and your conference slides.
- When you share it on social media, the preview uses your name, a short description and your photo.
- Optional: buy your own domain, like `tingxu.com` (about US$12 per year), and add it under **Settings → Pages → Custom domain**.
