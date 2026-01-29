# Kalyani Farm

Welcome — this repository contains the files for the Kalyani Farm site.

## Open the site
- Live (repo root): [Open site →](./index.html)

## Quick notes
- GitHub and most file browsers sort files alphabetically. To control the visual order of files in the repository listing, give filenames a prefix such as `01-`, `10-`, or `_`.
- If you use GitHub Pages, keep the homepage named `index.html` (lowercase) in the repository root — Pages expects `index.html` as the site entry point.

## Recommended file ordering
Rename files to add numeric prefixes so `index.html` (or your preferred landing file) appears first:
- `index.html` (or `01-Index.html` if not using Pages)
- `10-about.html`
- `20-contact.html`
- `assets/` (images, CSS, JS, etc.)

## How to rename safely (git)
If you want to rename files while preserving history, run:
```bash
git checkout main
git pull origin main
git mv Index.html 01-Index.html
git commit -m "Rename Index.html -> 01-Index.html to control listing order"
git push origin main
```
If your site uses GitHub Pages and must remain `index.html`, don't rename it — instead rename the other files (e.g. `10-about.html`) or use the README to present links in your desired order.

## Preview locally
Start a quick local server and open `index.html` in your browser:
```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

## Links & contact
- Repository: this repo
- For help updating links or moving files, open an issue or message me on the repo.

<!-- Optionally: add any other project-specific instructions below -->
