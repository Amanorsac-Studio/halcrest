# Halcrest Group LLC website

One-page static site for https://halcrestllc.com, served by a Cloudflare Worker (static assets only, no server code).

- Site files: `public/`
- Config: `wrangler.jsonc` (Worker name `halcrest`; custom domains halcrestllc.com and www.halcrestllc.com)
- Deploys automatically through Cloudflare Workers Builds on every push to `main`. Manual deploy: `npx wrangler deploy`.
