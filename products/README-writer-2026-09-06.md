> **Historical snapshot — not current product information.** This September 6, 2026 document may use retired 3CL/Nexus branding, superseded prices, or unshipped plans. It does not describe current company structure or availability. Use the [current product catalog](https://lumavel.co/products) and [current company overview](../README.md). Notice added November 7, 2026.

# Lumavel Writer

> Historical snapshot from September 2026. For current offerings, see the [product index](INDEX.md).

**As of:** 2026-09-06  
**Slug:** `writer`  
**Status:** beta

## What it is

A writing environment. **Web** at `/apps/writer` (Clerk, local drafts). **Desktop** Electron is still the heavier client. Same Lumavel account. Browser-first; store wraps later.

## Public door

- https://lumavel.co/apps/writer  
- Local: `pnpm --filter lumavel-website dev` → `:1132/apps/writer`  
- Desktop: `pnpm writer:dev` (`apps/electron-apps/lumavel-writer`)

## Where in this repo

- Web: `apps/lumavel-website/app/apps/writer`  
- Electron: `apps/electron-apps/lumavel-writer`  
- Contracts: `packages/lumavel-writer-contracts`  
- Runbook: `docs/lumavel-migration/17b-writer-monorepo-import.md`

## What it is not

- Not Iter. Not Publishing House. Not a second Vercel project.

## Next

Same “full app in the browser” depth as Korelira (web still thinner than desktop).
