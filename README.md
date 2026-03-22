# justicelee.dev

Personal portfolio website for Justice Lee, built with [Astro](https://astro.build/).

## 🚀 Project Structure

```
/
├── public/
│   ├── assets/
│   │   ├── backgrounds/   # Background images
│   │   └── *.jpg          # Project and profile images
│   ├── favicon.ico
│   └── favicon.svg
├── src/
│   ├── components/        # Reusable Astro components
│   ├── content/
│   │   └── work/          # Markdown files for work/projects
│   ├── layouts/           # Page layouts
│   ├── pages/             # Page components (routes)
│   └── styles/
│       └── global.css     # Global styles
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## 🧞 Commands

| Command         | Action                                       |
| :-------------- | :------------------------------------------- |
| `npm install`   | Install dependencies                         |
| `npm run dev`   | Start local dev server at `localhost:4321`   |
| `npm run build` | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally before deploying |

## 📝 Adding Work Projects

Add new Markdown files in `src/content/work/`. Each file requires this frontmatter:

```md
---
title: Project Title
publishDate: 2024-01-01 00:00:00
img: /assets/your-image.jpg
img_alt: Image description
description: Short project description
tags:
  - Tag1
  - Tag2
---

Your project content here...
```

## 🌐 Deployment

This site is deployed to [justicelee.dev](https://justicelee.dev) via GitHub Pages.
