# mahmud-hasans.github.io

Personal site of Mahmud Hasan Saikot. One page, plain HTML/CSS/JS, no build step.

## Files
| Path | What it is |
|---|---|
| `index.html` | The whole site (styles and scripts inside) |
| `assets/photo.jpg` | Profile photo |
| `assets/Mahmud_Hasan_Saikot_CV.pdf` | CV (replace the file, keep the name) |
| `assets/papers/` | Hosted paper PDFs |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Common edits (all in `index.html`)
- **Publications:** the `PUBS` list near the bottom of the file. Each entry has `link` (title link), `pdf`, optional `arxiv`, `code`, and `bib` (Cite button). New entries appear automatically.
- **NMI paper on release:** update the first `PUBS` entry: `link` → Nature article, `venue`, `bib`. Keep `arxiv`. The News item follows automatically.
- **TeCoBot links:** `TECOBOT_URL` (hero "Meet a cool robot") and `TECOBOT_PLAY` (card "Play with TeCoBots"), just above `PUBS`.
- **News / Projects / Experience / Awards:** plain HTML sections (Awards is the `AWARDS` list in the script).
- **Analytics:** paste the GoatCounter script just before `</body>`.

## Publishing / updating
Upload changed files to the `mahmud-hasans.github.io` repository (Add file → Upload files). The site rebuilds in 1–2 minutes.
