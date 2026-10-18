# #random-doo

A minimal personal notebook at https://doojinseo.github.io.

## Publish

In Settings → Pages, choose **Deploy from a branch**, **main**, **/(root)**, and Save.
GitHub Pages builds this Jekyll site automatically when changes are committed.

## Write a post

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md`:

```markdown
---
title: "Your title"
description: "A short introduction shown on the home page."
category: "Notes"
---

Write your post in Markdown here.
```

Use today's date or a past date. Future posts are hidden until the site is rebuilt after their date.
Edit or remove the clearly marked starter post when you're ready.

## Customize

- Blog title, description, and address: `_config.yml`
- About page: `about.md`
- Homepage: `index.html`
- Colors, spacing, and typography: `assets/style.css`

If you change your GitHub username, rename the repository to `NEW-USERNAME.github.io`, update `url` in `_config.yml`, and update the GitHub links in the layout and about page.

## Local preview (optional)

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000.
