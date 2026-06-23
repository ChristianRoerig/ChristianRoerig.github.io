# christianroerig.github.io

Personal academic website built with Astro and Tailwind CSS.

## Stack

- [Astro 5](https://astro.build/) — static site generator
- [Tailwind CSS 3.4](https://tailwindcss.com/) — utility-first styling
- GitHub Pages — hosting via GitHub Actions

## Development

```bash
npm install
npm run dev
```

## Deployment

Pushes to `master` automatically deploy via `.github/workflows/deploy.yml`.

## Slides sync

Teaching slides are synced weekly from Overleaf via `.github/workflows/sync-slides.yml`.
