[README.md](https://github.com/user-attachments/files/32835195/README.md)
# Daniel Huerta — UX Research Portfolio

A single-page portfolio site. No build step, no dependencies — just `index.html` and an `images/` folder.

## File structure

```
portfolio-site/
├── index.html
└── images/
    ├── avatar.jpg
    ├── k-admin-vs-testing.jpg
    ├── k-cover.jpg
    ├── k-dre-funnel.jpg
    ├── k-friction-points.jpg
    ├── k-mockup.jpg
    ├── x-diagnostic.jpg
    ├── x-dropout.jpg
    ├── x-dual-friction.jpg
    └── x-iteration.jpg
```

## Deploy with GitHub Pages (free, ~2 minutes)

1. Create a new repository on GitHub (e.g. `portfolio`).
2. Upload `index.html` and the whole `images/` folder to the repo root, keeping the same structure — do not rename files or the image paths will break.
   - Easiest way: on the repo page, click **Add file → Upload files**, then drag in `index.html` and the `images` folder together.
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, choose `main` and `/ (root)`, then **Save**.
6. Wait ~1 minute. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

## Editing content later

All copy lives directly in `index.html` as plain text — search for the section you want to change (`<h2>About</h2>`, `<h2>Work</h2>`, etc.) and edit the text between the tags. No rebuild needed; just commit and push, GitHub Pages updates automatically within a minute or two.

## Swapping images

Replace any file inside `images/` with a new one **using the exact same filename**, or update the `src="images/..."` path in `index.html` if you rename it.
