# mkc673.github.io

Personal blog and website built with [Jekyll](https://jekyllrb.com/) using the [Start Bootstrap Clean Blog](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll) theme, hosted on [GitHub Pages](https://pages.github.com/) at <https://mkc673.github.io/>.

## Project Structure

- `_config.yml` — Site configuration (title, description, social links, `remote_theme`, and plugins).
- `_posts/` — Blog posts named `YYYY-MM-DD-title.md`.
- `index.html` — Home page (displays hero masthead and recent posts).
- `posts/index.html` — Paginated archive of all blog posts (`/posts/`).
- `about.html` — About page (`/about`).
- `contact.html` — Contact page (`/contact`).
- `img/` — Header background images for pages and posts.
- `404.html` — Custom 404 error page.

## Adding a Post

Create a new Markdown file in `_posts/` named `YYYY-MM-DD-your-post-slug.md` with front matter:

```yaml
---
layout: post
title: "Your Post Title"
subtitle: "Optional subtitle"
date: 2026-11-21 12:00:00 -0500
background: '/img/bg-post.jpg'
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
