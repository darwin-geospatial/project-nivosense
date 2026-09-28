# status.md · `planning/`

**Last updated:** 2026-09-29
**Updated by:** Claude (planning rollout with gabriel)
**Covers:** all of `planning/`, including `reports/`

## Current state

Planning folder per DS-STD-001-006: data only (`status.md`, `ideas.md`, `data/`, `reports/`).
Workflows and builders are served by darwin-agent-center (`kb_planning_workflow()`,
`kb_planning_builders()`); nothing of the engine lives here. `data/items.csv` holds the header only: the root `IDEAS.md` (removed 2026-09-29; git history keeps it) had only empty template tables, so there were no rows to migrate. This repo is public: keep every row safe to publish.

## Open items

| Item | Status | Notes |
|---|---|---|
| Migrated rows without owner / importance / size | open | none (no rows) |
| `ROADMAP.md` | open | old planning material: Cassini Hackathon weekend roadmap (team split, Saturday and Sunday timeline); how to migrate is pending |
| `development_strategy.md` | open | old planning material: hackathon development strategy (objective, ML methodology, viewer features); how to migrate is pending |

## Project facts the workflows point to

| Fact | Detail |
|---|---|
| Retired ids | none |
| Confidentiality | see `AGENTS.md` |

## Last completed work

2026-09-29: planning folder created, IDEAS.md migrated to `data/items.csv`, dashboard built.

## Downstream status files

none (this file covers the report folders too).
