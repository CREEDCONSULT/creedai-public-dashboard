# CreedAI Public Dashboard

This repository is a sanitized static Cloudflare Pages site.

## Cloudflare Pages Settings

- Production branch: `main`
- Framework preset: `None`
- Build command: `exit 0`
- Build output directory: `/`
- Root directory: `/`

The repo root contains the top-level `index.html` required by Cloudflare Pages.

## Do Not Use Worker Deploy Commands

Do not run these commands for this repo:

```powershell
npx wrangler deploy
npx wrangler versions upload
```

Those commands deploy Cloudflare Workers. This project must deploy as Cloudflare Pages static HTML only.

## Public Files Only

The repository should contain only:

- `index.html`
- `.gitignore`
- `README.md`

Do not add Wrangler config, package files, dependencies, secrets, private CreedAI folders, or generated Cloudflare state.
