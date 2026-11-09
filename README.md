# Finance & Research Portfolio — Ehsan Khoddamy

Personal website built with [Quarto](https://quarto.org), hosted on GitHub Pages.

## What's in here

| File / folder | What it is |
|---|---|
| `_quarto.yml` | Site settings: title, menu, links, theme |
| `index.qmd` | Home page |
| `research.qmd` | Research overview (lists everything in `research/` automatically) |
| `projects.qmd` | Projects overview (lists everything in `projects/` automatically) |
| `about.qmd` | About & CV |
| `contact.qmd` | Contact |
| `research/fomc-study.qmd` | FOMC study page (template to fill) |
| `projects/*.qmd` | Dashboard and DCF pages (drafts, hidden until you remove `draft: true`) |
| `assets/cv.pdf` | Your CV (replace the placeholder) |
| `theme.scss`, `styles.css` | Colours, fonts and layout |

Yellow highlighted text in the preview is a placeholder (`[...]{.todo}` in the source). Search for `todo` to find them all.

## 1. Run it on your computer

1. Install Quarto: https://quarto.org/docs/get-started/
2. Install VS Code and the "Quarto" extension.
3. Open this folder in VS Code, open a terminal and run:

   ```
   quarto preview
   ```

   Your browser opens the site. It refreshes every time you save a file.

## 2. Add your content

- Replace `assets/cv.pdf` with your real CV (same file name).
- Fill the placeholders in `about.qmd`, `contact.qmd` and `research/fomc-study.qmd`.
- To publish a project: open the file in `projects/`, fill it, delete the line `draft: true`.

**Never publish** confidential Nespresso or investment-bank data, restricted SOEP data, or unpublished thesis material without permission.

## 3. Publish on GitHub Pages

The finished website is built into the `docs/` folder. GitHub Pages serves that folder directly.

1. On GitHub, create a **public** repository named `ehsankhoddamy.github.io`.
2. Upload this whole folder to it (or push it with git).
3. On GitHub: Settings → Pages → "Deploy from a branch" → branch `main`, folder `/docs` → Save.

The site is live at https://ehsankhoddamy.github.io a minute or two later.

**After later edits:** run `quarto render` (this updates `docs/`), then upload or push the changed files again.
