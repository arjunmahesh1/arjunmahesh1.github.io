# arjunmahesh1.github.io

Personal academic site, served by GitHub Pages at https://arjunmahesh1.github.io

## Structure

```
index.html                    # Homepage (bio + photo) — GitHub Pages requires this at the root
research/index.html           # Research tab
writing/index.html            # Writing tab — "All" posts
writing/geography/index.html  # Writing → Geography subpage
assets/css/style.css          # Shared stylesheet (Roboto, navy #002244)
assets/images/home_page.jpg   # Web-sized homepage photo
assets/images/home_page_full.jpg  # Original full-resolution photo
```

## Editing

- **Homepage bio**: edit the paragraphs inside `<div class="intro-text">` in `index.html`.
- **Adding a post**: create an HTML file (e.g. under `writing/posts/`), then link it in the
  `<ul class="post-list">` in `writing/index.html` — and also in `writing/geography/index.html`
  if it's a geography post.
- **Colors/fonts**: everything is in `assets/css/style.css` (`--navy` variable at the top).

## Publishing

Push to `main`. In the repo's Settings → Pages, make sure the source is set to
"Deploy from a branch" with branch `main` and folder `/ (root)`.
