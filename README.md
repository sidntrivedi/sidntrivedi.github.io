# Siddhant N Trivedi

Personal blog built with [Astro](https://astro.build) using the
[Astro Cactus](https://github.com/chrismwilliams/astro-theme-cactus) template.

## Development

```sh
npm install
npm run dev
```

The dev server runs at `http://localhost:4321/` by default.

## Build

```sh
npm run build
npm run preview
```

Production output is written to `dist/`. The build also runs Pagefind so the
static search index is generated.

## Content

Blog posts live in `src/content/post/`. The filename is the post slug, so
`src/content/post/gsoc-report1.md` is served at `/posts/gsoc-report1/`.

Tag metadata lives in `src/content/tag/`.

Site metadata, navigation, and date formatting live in `src/site.config.ts`.
