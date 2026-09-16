# Rann Mahal — A Palace at the Desert’s Edge

Scroll film: a 240-frame WebP sequence scrubbed by scroll, with five chapters and a closing panel over it. Built for the Scroll Sites marketplace, iframe-ready.

- `npm run dev` / `npm run build` → `dist/` (`BASE=/repo-name/` for GitHub Pages)

## Live URLs
- Vercel (primary): https://rann-mahal-scroll-site.vercel.app
- GitHub Pages (mirror): https://husnainkhushid.github.io/rann-mahal-scroll-site/

Both deploy on push to `main`. Vercel uses the Vite preset with no config; the Pages workflow sets `BASE`.

## For the coding agent
Section resources live in the marketplace workspace under `02-sections/rann-mahal/`. Section ids: `01-chapter … 05-footer` (`data-section` attributes). The page posts `{ source:'scroll-site', type:'sections'|'section' }` to a parent frame and accepts `{ type:'scrollTo', id }`.
