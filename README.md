# todcubed blog

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

## Features

- Individual post pages with readable typography and topic tags
- Search across post titles, excerpts, and tags
- RSS/Atom feed at `/blog/feed.xml`
- About page, responsive layout, and SEO metadata
- Relative links configured for the `/blog` project-site path

## GitHub Pages setup

In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. GitHub Pages should process the Jekyll files. If Pages is already enabled, commits to `main` trigger a build automatically.

## Local preview

Install Ruby and Bundler, then use the GitHub Pages gem for a close local preview:

```sh
gem install bundler
gem install github-pages
jekyll serve --baseurl /blog
```

Open <http://localhost:4000/blog/>.
