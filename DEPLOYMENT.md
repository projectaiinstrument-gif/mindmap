# Deployment

MIND MATRIX is a static, single-file web application.

- Entry point: `index.html`
- Build command: none
- Output directory: repository root
- Install command: none

## Vercel
Create a separate Vercel project connected to this repository. Keep the existing `mindmap1` Vercel project connected to `projectaiinstrument-gif/mindmap1`; do not repoint it.

Set the framework preset to Other (or no framework), leave the build command empty, and serve the repository root. Deploy from the `main` branch after reviewing the standalone branch.

## Local use
Open `index.html` directly in a modern browser. No backend is required for the core map and interview features.
