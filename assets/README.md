# Assets

Drop the real files here — the site references them by these exact names:

- `cv.pdf` — your CV. Linked from the nav, hero "View CV" button, and footer.
  Opens in a new tab (browsers render PDFs natively).
- `photo.jpg` — your portrait, ideally 4:5-ish crop (e.g. 800×1000), under
  ~300KB. Shown in the hero.

To update either later: overwrite the file, then `git add -A && git commit &&
git push` — GitHub Pages redeploys automatically in ~1 minute. No HTML changes
needed; the page points at the filename, not an embedded copy.

Note: this repo is PUBLIC — anything here (including the CV) is downloadable
by anyone. Strip phone number / street address from the CV if that bothers you.
