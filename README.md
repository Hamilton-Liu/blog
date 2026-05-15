# Personal Blog

Astro static blog optimized for GitHub Pages. Posts live in `src/content/blog/` and can be written in Markdown or MDX.

## Local Development

```sh
npm.cmd install
npm.cmd run dev
```

Build before publishing:

```sh
npm.cmd run build
```

## Publish to GitHub Pages

1. Create a GitHub repository.
2. Push this project to the `main` branch.
3. In GitHub, open `Settings -> Pages`.
4. Set `Source` to `GitHub Actions`.
5. Push new commits. The workflow in `.github/workflows/deploy.yml` builds and deploys `dist/`.

For a project page, the final URL is usually:

```text
https://<your-github-username>.github.io/<repository-name>/
```

For a user page repository named `<your-github-username>.github.io`, the workflow automatically uses `/` as the base path.

## Writing

Create a new file under `src/content/blog/`:

```md
---
title: "My Post"
description: "Short summary for SEO and RSS."
pubDate: 2026-05-15
---

Post content goes here.
```
