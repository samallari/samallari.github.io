# Samantha Mallari — portfolio starter

Based on [AstroPaper](https://github.com/satnaing/astro-paper), with the original home sections, posts, tags, about page, archives, RSS, and Pagefind search. The template’s example posts are intentionally retained as editable examples.

## Run locally

Use Node.js 24 (minimum 22.12).

```sh
npm install
npm run dev
```

Visit http://localhost:4321. For a production build and working search:

```sh
npm run build
npm run preview
```

## Customize

- `astro-paper.config.ts`: name, description, social links, feature settings.
- `src/styles/theme.css`: cream `#FEF3D9`, navy `#060B1A`, sage `#A8BFA8`, pink `#E8B7C8`. Light-mode links use a darker sage for readable contrast.
- `astro.config.ts`: Space Mono font, self-hosted through Astro’s font loader.
- `src/pages/index.astro`: home introduction and base template sections.
- `src/content/pages/about.md`: about text.
- `src/content/posts/`: Markdown/MDX entries; set `featured: true` to show an entry in Featured, or `draft: true` to hide it.
- `public/favicon.svg`: temporary branded SM favicon, ready to replace with your logo.

The existing Jekyll portfolio, images, projects, papers, essays, and resume are preserved in `legacy/` as migration references; Astro does not publish that folder. Projects, Papers & Presentations, and CV can be added in the next customization pass.

The GitHub Pages workflow builds Astro and deploys only from `main`. Work on `dev` stays local until you push or merge it. The original template’s MIT license is retained in `LICENSE`.

## Publication destinations

In `src/content/publications/*.md`, set `link` to a website URL or a local PDF path:

```yaml
link: "https://example.com/paper"
# Or upload a PDF to public/papers/my-paper.pdf and use:
# link: "/papers/my-paper.pdf"
```

Publication cards and Featured Papers titles use this destination. An empty `link` keeps the internal publication page as the destination.

To show a publication in Featured Publications on the homepage, add `featured: true` to its frontmatter. The default is `false`; only published, featured entries appear, newest first.
