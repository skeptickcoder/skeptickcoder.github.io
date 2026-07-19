# Assets

The site references these exact filenames:

- `Guy_Leibu_CV_Solution_Engineer_2026.pdf` — the CV. Linked from the nav,
  hero "View CV" button, and footer. Opens in a new tab. If you replace it
  with a differently-named file, update the three hrefs in ../index.html too
  (or keep the same name and just overwrite).
- `photo.jpg` — the hero portrait (real JPEG, ~63KB, 634×622; the page crops
  it to 4:5 with object-fit: cover). Overwrite to update.

To update either later: overwrite the file, then `git add -A && git commit &&
git push` — GitHub Pages redeploys automatically in ~1 minute. No HTML changes
needed; the page points at the filename, not an embedded copy.

Note: this repo is PUBLIC — anything here (including the CV) is downloadable
by anyone. Strip phone number / street address from the CV if that bothers you.
