# Artem Pidhornyi — CV

Personal CV as a single static HTML page, ready for GitHub Pages.

## Structure

- `index.html` — the whole site (content + styles in one file, no build step)
- `certificates/` — certificate PDFs linked from the page

## Deploy on GitHub Pages

1. Create a repository (e.g. `cv`, or `<username>.github.io` to get the root URL).
2. Push the contents of this folder to the repository root.
3. In the repo: **Settings → Pages → Source: Deploy from a branch**, branch `main`, folder `/ (root)`.
4. The site appears at `https://<username>.github.io/<repo>/` within a minute or two.

## Editing

All content lives in `index.html` — it is plain HTML, edit the text directly.
The **Print / Save as PDF** button uses a print stylesheet, so the same page doubles as a printable resume.
