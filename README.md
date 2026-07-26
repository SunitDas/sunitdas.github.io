# Sunit Das, Personal Website

A static site (plain HTML/CSS/JS, no build step) with pages: Home, Research, Publications, Academic Background, Contact.

## Add your photo first

Save your profile photo as **`assets/profile.jpg`** (square crop works best, roughly 400x400 px or larger).
Until you do, the homepage falls back to a plain placeholder so the layout stays intact.

## Deploy on GitHub Pages (free, about 5 minutes)

1. Create a GitHub account at github.com if you don't have one.
2. Create a new **public** repository. Naming it `<your-username>.github.io` gives you a clean root URL; any other name (such as `personal-site`) also works.
3. Upload everything in this folder: `index.html`, `research.html`, `publications.html`, `background.html`, `contact.html`, `README.md`, and the `css/`, `js/`, and `assets/` folders. Use the GitHub web UI ("Add file" then "Upload files") or `git push`. Make sure `index.html` sits at the repository root, not inside a subfolder.
4. In the repository, go to **Settings**, then **Pages**.
5. Under "Build and deployment", set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
6. Wait a minute or two. Your site will be live at:
   - `https://<your-username>.github.io/` if the repo is named `<your-username>.github.io`, or
   - `https://<your-username>.github.io/<repo-name>/` otherwise.

## Updating content later

Every file is plain text. Edit directly on GitHub (pencil icon on any file) or locally and push. No rebuild step needed.

Common edits:

- **News items:** the `news-list` block in `index.html`.
- **New paper:** copy an existing `<div class="pub">` block in `publications.html` and adjust.
- **Research themes:** each theme is a `<div class="card">` in `research.html`, with its citations in the `refs` block at the bottom.

## Notes

- The CV button links to your Google Drive file. If you later prefer a self-hosted copy, drop the PDF into `assets/` and point the link there instead.
- No images are hot-linked from external hosts, so the site is fully self-contained apart from the CV link.
