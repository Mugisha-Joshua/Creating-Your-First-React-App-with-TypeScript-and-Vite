# My First React App

The app built for the Week 2 guided activity: a single custom component,
`MyComponent`, that renders a heading and a paragraph and is styled from its own
CSS file. See the [activity instructions](../README.md) for the full walkthrough.

## Run it locally

```bash
npm install
npm run dev
```

Vite prints a local URL, usually http://localhost:5173/.

| Script | What it does |
| --- | --- |
| `npm run dev` | Start the development server with hot reloading |
| `npm run build` | Type-check with `tsc` and build for production |
| `npm run preview` | Serve the production build locally |
| `npm run lint` | Lint the source with oxlint |

## Source layout

- `src/main.tsx` — entry point; mounts `App` into `index.html`
- `src/App.tsx` — renders `MyComponent`
- `src/MyComponent.tsx` / `src/MyComponent.css` — the custom component and its styles
- `src/App.css`, `src/index.css` — layout and global styles
