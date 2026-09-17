## 🚀 Project Structure

```text
├── public/
│   └── favicon.svg
├── src
├── assets
│   ├── astro.svg
│   └── background.svg
├── components
│   └── Welcome.astro
├── content
│   └── rules
│       └── hello.md
├── content.config.ts
├── layouts
│   └── Layout.astro
├── pages
│   ├── index.astro
│   └── [slug].astro
└── styles
│   └── global.css
└── package.json
```

All you have to do is create new file or edit one in the rules folder.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |
| `pnpm astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                     |
