# MM Builders & Infrastructure — Frontend

This is the supplied MM Builders portfolio design packaged as a runnable Vite frontend. The original HTML, styling, animations, and client-side interactions are preserved in `index.html`.

## Requirements
- Node.js 18 or newer
- npm

## Run locally
1. Extract the ZIP.
2. Open the extracted `MM_Builders_Frontend` folder in VS Code.
3. Open Terminal → New Terminal.
4. Run:

   ```bash
   npm install
   npm run dev
   ```

5. Open the local URL printed by Vite (usually `http://localhost:5173`).

## Build for deployment

```bash
npm run build
npm run preview
```

The production site is generated in `dist/`.

## Project contents
- `index.html` — full portfolio page (HTML, CSS, and JavaScript).
- `public/assets/mm_logo_gold.png` — supplied logo asset.
- `public/assets/concepts/` — supplied architectural concept videos.
- `public/assets/blueprints/` — supplied interactive 3D blueprint HTML pages.

## Notes
- The portfolio HTML includes some media as embedded data, so the page can display those assets without separate image files.
- The concepts videos and blueprint files are included as separate assets for the project.
- This is a frontend-only package. Contact/enquiry form submission, if it needs to deliver enquiries to an admin or database, will require a backend/API endpoint and configuration.
