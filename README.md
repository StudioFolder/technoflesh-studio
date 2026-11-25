# technoflesh-studio

New website for /technoflesh Studio (Simone C Niquille), designed and developed by Studio Folder.

An object-based archive generated from Simone's Obsidian vault as a static site.

## Stack

- [Astro](https://astro.build) 7, static output
- [Svelte](https://svelte.dev) 5 for interactive components (`@astrojs/svelte`)
- Node ≥ 22.23.4

## Run

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # static site in dist/
npm run preview  # serve the build locally
```

## Structure

```
src/
  pages/       routes (index.astro)
  layouts/     page shells (Base.astro)
  components/  Astro and Svelte components
public/        static files served as-is
```

No content or content model yet.

## Workflow

- **Code:** this repo
- **Content:** Simone's Obsidian vault (separate repo, to be set up)
- **Dev and previews:** Vercel (Studio Folder account)
- **Production:** static build deployed to Simone's hosting at handover

## Project materials

`Folder_WORKS/2027_TFS_Technoflesh studio website` (references, call notes)
