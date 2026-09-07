# README naming — status snapshots

**As of:** 2026-09-06

When you write a product or company status note, **put the date in the filename**. Search by date to see what is current.

## Filename

```text
README-{product-slug}-{YYYY-MM-DD}.md
```

| Part | Rule | Example |
|------|------|---------|
| Prefix | Always `README-` (uppercase) | `README-` |
| Product | Lowercase, hyphens, no spaces | `korelira`, `iter-discendi`, `lumavel-business` |
| Date | ISO date of the snapshot | `2026-09-06` |

**Good:** `README-korelira-2026-09-06.md`  
**Bad:** `Korelira_README.md`, `readme-korelira.md`, `README.md` used as the only dated note

## Where the files live

| Kind | Path |
|------|------|
| **Search folder (all snapshots)** | `docs/status-readmes/` |
| **Also next to the product** | App or docs folder, same filename |
| **Index** | `docs/status-readmes/INDEX.md` |

Keep a short `README.md` in the app for commands. First line: link to the **latest** dated snapshot.

## When to write a new file

Write a **new dated file**. Do not rename yesterday’s file. Old dates stay so history is searchable.

## Required sections (copy this)

```markdown
# {Product name}

**As of:** YYYY-MM-DD  
**Slug:** `{product-slug}`  
**Status:** live | beta | coming-soon | planned | internal | parked

## What it is

One paragraph. People first. Not marketing fluff.

## Public door

- Production URL (lumavel.co/…)
- Local (if any): `pnpm --filter …`

## Where in this repo

- Code / docs paths

## What it is not

- Sister products it is not

## Next

- Highest-leverage next work
```

## Masters (always keep current)

| File | Scope |
|------|--------|
| `README-lumavel-nexus-{date}.md` | Entire private monorepo |
| `README-lumavel-business-{date}.md` | Lumavel business / Hub / Plaza / tools |
| Public company face | `docs/github/LUMAVEL_ORG_PROFILE_README.md` → GitHub `Lumavel/Lumavel-Public` |
