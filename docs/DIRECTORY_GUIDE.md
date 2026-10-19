# SkyrimNG Directory Guide

This repository owns the **modlist**, not Companion application code. Each directory's README defines its detailed conventions.

| Path | Responsibility | Expected contents |
|---|---|---|
| `architecture/` | Modpack-wide design decisions | Runtime strategy, design decision records, component boundaries |
| `separators/` | MO2 left-pane organization | Stable separator identifiers, category taxonomy, ordering rules |
| `compatibility/` | Evidence-backed conflicts and fixes | Mod/version rules, conflict investigations, resolutions |
| `patches/` | Custom patch provenance | Patch manifests, masters, build steps, validation evidence |
| `manifests/` | Portable modpack inventory | Sanitized MO2 snapshots, version identifiers, reproducible metadata |
| `testing/` | Quality assurance | Test plans, regressions, performance and gameplay evidence |
| `releases/` | Wabbajack distribution readiness | Compilation checklist, installation validation, release notes |
| `sessions/` | Durable session handoffs | Current handoff, archived milestones, evidence references |
| `prompts/` | Reusable AI workflow prompts | Start and end session instructions |
| `docs/` | Cross-cutting repository guidance | Directory map, policies, contributor instructions |

**Do not store** mod archives, unlicensed third-party assets, private machine paths, credentials, or unreviewed binary outputs in Git.
