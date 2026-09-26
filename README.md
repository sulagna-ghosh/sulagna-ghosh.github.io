# Personal website

Files:
- `index.html` — the whole site (styles are inline, no build step)
- `cv.pdf` — your CV (replace whenever you update it)
- `photo.jpg` — add a square headshot with this filename (any size; it is displayed at 150px)

## Hosting on GitHub Pages

1. Create a new **public** repository on GitHub named exactly `<your-username>.github.io`.
2. Upload `index.html`, `cv.pdf`, and `photo.jpg` to it (drag-and-drop on the GitHub website works; no git needed).
3. Wait a minute or two, then visit `https://<your-username>.github.io`.

That's it. GitHub Pages serves the repository root automatically for a repo with that name.
If it doesn't appear, go to the repo's Settings → Pages and make sure Source is "Deploy from a branch", branch `main`, folder `/ (root)`.

## Editing

Open `index.html` in any text editor. The things you'll update most often:
- Links at the top (Google Scholar, GitHub) — currently placeholders
- The `#publications` list — copy one `<li>` block and edit it
- The "Last updated" line in the footer
