# Contributing

Thanks for wanting to contribute! This project stores blog posts as Markdown files in the `posts/` folder. Follow these steps to add a new post or contribute changes.

## Before you start
- Fork the repository and create a branch named `add/<short-description>` or `fix/<short-description>`.

## Adding a new post
1. In the `posts/` directory create a new Markdown file with a descriptive filename, for example `2026-03-12-note-of-the-day.md` or `my-first-post.md`.
2. At the top of the file include a short frontmatter block (YAML) with at least these fields:

---
title: "My Post Title"
date: "2026-03-12"
author: "Your Name"
tags: [tag1, tag2]
---

3. Write your content below the frontmatter using standard Markdown.
4. Keep images and assets in `public/` and reference them with relative paths.

## Commit message and branch conventions
- Use a concise commit message describing the change (e.g., "Add: my-first-post").
- Branch name format: `add/<short-description>` or `fix/<short-description>`.

## Tests and preview
- There are no automated tests for posts. Run the app locally to preview your post:

```
# install deps if needed
npm install
# start server
node server.js
```

Open `http://localhost:3000` (or the configured port) and verify your post appears as expected.

## Pull request
- Open a pull request from your branch to the `main` branch with a clear description of your change.
- Link any related issue if applicable.

## Code style and review
- Keep Markdown clean and readable. Use headings, paragraphs, and lists where appropriate.
- A maintainer will review your PR and may request changes. Please respond to feedback.

## Contact
- If you need help, open an issue or tag a maintainer in the PR.

Thanks — we look forward to your contribution!
