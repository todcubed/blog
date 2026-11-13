# My blog

A lightweight, searchable Jekyll blog published at <https://todcubed.github.io/blog/>.

## Publishing

Posts are Markdown files in `_posts/`. Create a file named `YYYY-MM-DD-your-post-title.md` and add front matter at the top:

```yaml
---
layout: post
title: "Your post title"
date: 2026-11-13 10:00:00 -0000
description: "A short summary for the post list and search engines."
tags: [notes, projects]
---
```

Write the post below the closing `---` using Markdown. Commit the file to `main` to publish it. GitHub Pages builds the Jekyll site automatically; the date in the filename and front matter should match. Posts dated in the future will not appear until that date.
