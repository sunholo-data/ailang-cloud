# AILANG Cloud landing page

The static landing page served at <https://www.sunholo.com/ailang-cloud/>.

GitHub Pages serves a project site under the repository's name, which is why this page lives in a
repository called `ailang-cloud` (the same arrangement as `blog` and `presentations`).

- `index.html`, `styles.css` — the page.
- `.github/workflows/pages.yml` — deploys on every push to `main`. It publishes exactly
  `index.html`, `styles.css` and `.nojekyll`; add a file to that list to publish it.

**This repository is public and everything the workflow stages is published.** Do not keep
operational notes, drafts or anything private here.

History: the page was first published from a private infrastructure repository, whose Pages
workflow uploaded its whole `docs/` folder. It moved here on 2026-11-10 so the public page no
longer shares a folder with private notes.
