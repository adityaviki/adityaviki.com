# adityaviki.com

My personal website. Built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com).

## Features

- Blog with Markdown/MDX support
- Project pages with Mermaid diagrams and image galleries
- Dark/light mode (toggle or press `d`)
- Minimal, content-focused design
- Fully static, fast by default

## Getting started

```sh
npm install
npm run dev
```

Open [localhost:4321](http://localhost:4321) to view the site.

## Adding content

Create Markdown or MDX files in `src/content/`:

- `src/content/blog/` — Blog posts (`.md` or `.mdx`)
- `src/content/projects/` — Project entries (`.md` or `.mdx`)

Project images go in `public/images/<project-name>/`.

See `src/content.config.ts` for the frontmatter schema.

## Commands

| Command          | Action                                  |
| :--------------- | :-------------------------------------- |
| `npm run dev`    | Start dev server at `localhost:4321`    |
| `npm run build`  | Build production site to `./dist/`      |
| `npm run preview`| Preview production build locally        |

## Deployment

Deployed on [Vercel](https://vercel.com). Pushes to `main` trigger auto-deploy.
