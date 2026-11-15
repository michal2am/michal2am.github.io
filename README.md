# michal2am.github.io

Personal academic homepage, served by GitHub Pages at https://michal2am.github.io/

Plain HTML, no build step. Everything is in `index.html` (styles included).

## Editing

- **Position, affiliation, links**: top of `<body>`, marked `EDIT`.
- **New paper**: copy one `<li>` block to the top of the list in the Publications section. Numbering updates automatically.
- **Projects**: each project is one `<article class="project">` block.
- **Student materials**: copy the commented template in the "For students" section. Files go in `materials/`; live Notion pages are linked as cards (publish the page in Notion first: Share > Publish, then use the public notion.site link).

## Publishing

1. Commit `index.html`, `.nojekyll`, `README.md` and `materials/` to the `main` branch.
2. Repository Settings > Pages > Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The page is live at https://michal2am.github.io/ within a minute or two.

`.nojekyll` tells GitHub to serve the files as they are.
