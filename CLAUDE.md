# CLAUDE.md
This file provides guidance to Claude Code when working with code in this repository.

## Commands
```bash
npm run dev       # Start dev server with HMR
npm run build     # Type-check (tsc -b) then bundle with Vite
npm run lint      # Run ESLint
npm run preview   # Preview production build locally
```
No test runner is configured yet.

## Stack
- **Astro** + **TypeScript**
- **Tailwind CSS**
- **Cloudflare Workers** (wrangler.jsonc)

## Environment
Running on Debian 13 VM (debian13-srv, 192.168.1.14) hosted on Synology DS1621+.
GitHub user: `lwainberg`.
NAS temp folder accessible at `/mnt/nas-temp`.
