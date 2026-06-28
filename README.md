# Oanh Tran Personal Website

This is my personal academic website built with Jekyll and GitHub Pages.

## Common Edits

### Change the About page

Edit:

```text
_pages/about.md
```

This file contains the main bio, useful links, News section, and the Publications list.

### Add or update News

Edit the `News` section in:

```text
_pages/about.md
```

Add a new bullet at the top:

```markdown
- **Month Year:** Your update here.
```

### Add a publication

Create a new Markdown file in:

```text
_publications/
```

Use a filename like:

```text
YYYY-MM-DD-short-paper-title.md
```

Copy this template:

```markdown
---
title: "Paper title"
collection: publications
permalink: /publication/YYYY-MM-DD-short-paper-title
excerpt: "One sentence summary."
date: YYYY-MM-DD
venue: "Venue name"
paperurl: "https://paper-link"
citation: "Author list. Paper title. Venue, Year."
---

Short description of the paper.
```

### Add a blog post

Create a new Markdown file in:

```text
_posts/
```

Use this filename format:

```text
YYYY-MM-DD-short-title.md
```

Use this template:

```markdown
---
title: "Post title"
date: YYYY-MM-DD
permalink: /blog/post-title/
tags:
  - research
---

Write the blog post here.
```

The blog index is at:

```text
_pages/year-archive.html
```

Normally you do not need to edit it.

### Change the profile photo

Replace these files:

```text
images/profile_image.jpeg
images/profile_avatar.jpeg
```

`profile_image.jpeg` keeps the original photo. `profile_avatar.jpeg` is the cropped sidebar avatar used by the site.

The avatar is configured in:

```text
_config.yml
```

Look for:

```yaml
author:
  avatar: "profile_avatar.jpeg"
```

### Replace the resume

Replace:

```text
files/My_resume_2026_Jan.pdf
```

The About page links to this file.

### Change navigation

Edit:

```text
_data/navigation.yml
```

Current main pages are About and Blog.

## Preview Locally

Install dependencies:

```bash
bundle install
```

Start the local site:

```bash
bundle exec jekyll serve
```

Open:

```text
http://localhost:4000
```

Note: this site may need Ruby 3+ for current GitHub Pages dependencies.
