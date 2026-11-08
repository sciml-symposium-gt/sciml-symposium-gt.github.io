# Student Symposium Website

Static HTML/CSS site (no build step) for hosting on GitHub Pages.
Derived from the SciML Symposium @ GT 2024 site, which is built on
[mikepierce/conference-website-template](https://github.com/mikepierce/conference-website-template) (GPL v3).

## Edit
- `index.html` – title, dates, about, code of conduct, schedule summary, speakers, organizers
- `program/index.html` – detailed schedule with abstracts (copy a `<table>` block per talk)
- Search for `TODO` to find every placeholder.
- Put photos in `assets/` (about 400px wide works well).

## Preview locally
`python3 -m http.server 8000` then open http://localhost:8000

## Publish
Settings → Pages → Deploy from branch → `main` / root.
