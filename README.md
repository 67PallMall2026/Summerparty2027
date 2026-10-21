# 67 Pall Mall Melbourne Summer Party 2027

Single-page event microsite. Saturday 6 February 2027, Studley Park Boathouse, Kew.

## Structure
- `public/index.html`: the page
- `public/assets/`: photography, summer artwork (canopy + script lockup), bronze logo
- `public/fonts/`: Messina Serif / Messina Sans (confirm the licence covers web embedding)
- `public/robots.txt`, `public/_headers`: keep the page out of search
- `wrangler.jsonc`: Cloudflare Workers static-assets config

## Deploy (Cloudflare)
Workers & Pages → Create → Import a repository → this repo.
Build command: blank. Deploy command: `npx wrangler deploy`.
The project name must match `"name"` in `wrangler.jsonc`.

## Before launch
- Replace the placeholder booking link: search `index.html` for `67-pall-mall-melbourne-club-events` (7 buttons).
