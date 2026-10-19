# SkyrimNG Project State

Last documented: 2026-10-19
Status: Foundation setup; no modpack build or scan verified.

## Confirmed decisions
- Target: eventual public Wabbajack release.
- Mod manager: Mod Organizer 2 (MO2).
- Runtime: undecided. Skyrim 1.5.97 is under consideration; it is the SE executable, potentially used with compatible AE/Creation Club content. Do not treat runtime as locked.
- Build approach: start fresh; retain the existing small modpack as a reference.
- Companion: deep MO2 integration is a long-term goal, beginning with read-only scanning.
- Persistence: GitHub files and local database are authoritative, not conversation context.

## Not yet verified
- MO2 installation paths, active profile, actual runtime and SKSE versions.
- Installed mod inventory, plugin ordering, patch status, and separator structure.
- Working Companion code or database.

## Next actions
1. Establish handoff workflow and directory skeletons.
2. Define read-only scanner input/output contracts.
3. Choose runtime based on actual mod requirements.
4. Create fresh isolated MO2 development instance.
5. Build and validate first scan against MO2.

## Synchronization rule
This document is a curated summary, not an automatic live status feed. Update it after verified milestones and link evidence in session handoffs.
