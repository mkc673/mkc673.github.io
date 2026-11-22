---
layout: post
title: "Welcome to My Blog!"
subtitle: "Getting started with Jekyll and the Clean Blog theme on GitHub Pages"
date: 2026-11-21 21:00:00 -0500
background: '/img/bg-post.jpg'
categories: general
---

Welcome to the first post on my new Jekyll site!

This blog is powered by [Jekyll](https://jekyllrb.com/), styled with the [Clean Blog](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll) theme, and hosted on [GitHub Pages](https://pages.github.com/).

## Writing New Posts

To add a new post, create a file in the `_posts` directory using the naming convention:

```text
_posts/YYYY-MM-DD-title-of-post.md
```

Include the required YAML front matter at the top of the file:

```yaml
---
layout: post
title: "Your Post Title"
subtitle: "An optional subtitle for the post header"
date: YYYY-MM-DD HH:MM:SS -0500
background: '/img/bg-post.jpg'
categories: [category1, category2]
---
```

## Example Code Block

Jekyll supports syntax highlighting out of the box:

```python
def greet(name: str) -> None:
    print(f"Hello, {name}! Welcome to my Jekyll blog.")

greet("world")
```
