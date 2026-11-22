# mkc673.github.io

Personal blog and website built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/) at <https://mkc673.github.io/>.

## Project Structure

- `_config.yml` — Site configuration (title, description, URL, theme, and plugins).
- `_posts/` — Blog posts named `YYYY-MM-DD-title.md`.
- `index.markdown` — Home page (uses Minima's `home` layout to list posts automatically).
- `about.markdown` — About page (`/about/`).
- `404.html` — Custom 404 error page.
- `Gemfile` — Ruby dependencies for local development with the `github-pages` gem.

## Adding a Post

Create a new Markdown file in `_posts/` named `YYYY-MM-DD-your-post-slug.md` with front matter:

```yaml
---
layout: post
title: "Your Post Title"
date: 2026-11-21 12:00:00 -0500
categories: notes
---

Write your post content here in Markdown.
```

## Local Development (Optional)

If you have Ruby and Bundler installed:

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000/`.
