# punat

A GitHub Pages for writings about our holiday home in Punat — Markdown posts with a clean, readable view powered by [Jekyll](https://jekyllrb.com) and the [Minima](https://github.com/jekyll/minima) theme. The pages are live at [https://vedranaa.github.io/punat/](https://vedranaa.github.io/punat/).
 

## Adding a new post

Create a file in `_posts/` following the naming convention `YYYY-MM-DD-title.md`, for example:

```
_posts/2026-07-20-the-monastery-island.md
```

Start every post with front matter:

```yaml
---
layout: post
title: "The Monastery Island"
date: 2026-07-20
---

Your writing goes here...
```

## Local preview

```bash
gem install bundler jekyll
bundle exec jekyll serve
```

Then open <http://localhost:4000> in your browser.

## Deployment

Every push to `main` triggers the GitHub Actions workflow in `.github/workflows/pages.yml`, which builds the site and deploys it to GitHub Pages automatically.
