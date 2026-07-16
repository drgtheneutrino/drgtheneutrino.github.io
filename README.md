# dangillphysics.com

Personal site for Daniel Gill. Plain HTML and CSS, no build step, hosted on GitHub Pages.

## Structure

- `index.html` covers the hero, about, research features, projects, gallery, and contact
- `research/` holds the two flagship write-ups
- `resume.html` mirrors the Word resume, with PDF and docx downloads in `assets/docs/`
- `assets/css/style.css` is the single stylesheet, design tokens at the top in `:root`
- `CNAME` keeps the custom domain bound to GitHub Pages, do not delete it

## Updating

Add gallery photos by dropping images in `assets/img/` and copying a `<figure>` block
in the gallery section of `index.html`. Replace the resume by overwriting the two files
in `assets/docs/` and editing `resume.html` to match.
