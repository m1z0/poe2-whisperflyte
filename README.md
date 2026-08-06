# Whisperflyte Build Tracker

Personal optimization journal for **Whisperflyte**, a level 93 Deadeye in the Runes of Aldur league.

## Character links

- [Whisperflyte on poe.ninja](https://poe.ninja/poe2/profile/BatseBayan-2892/runesofaldur/character/Whisperflyte)

## Current snapshot

| Metric | Current | Near-term target |
|---|---:|---:|
| Life | 1,674 | 1,850–2,000 |
| Energy Shield | 1,129 | Maintain 1,100+ |
| Evasion | 17,427 | Maintain 17,000+ |
| Fire Resistance | 74% | Cap, then 15%+ overcap |
| Cold Resistance | 75% | 15%+ overcap |
| Lightning Resistance | 75% | 15%+ overcap |
| Chaos Resistance | 17% | 35–50% |
| Strength | 78 / 45 required | Preserve a safe margin |
| Dexterity | 171 / 163 required | 175+ preferred |
| Intelligence | 117 / 115 required | 130–140 preferred |
| Combined PoB DPS | ~41,220 | Improve after defensive foundation |

## Current objective

1. Replace **Bramble Loop** with a life/fire/chaos resistance attack ring.
2. Evaluate a limited passive reassignment from Strength to Intelligence.
3. Upgrade the belt without losing three charm slots.
4. Upgrade the amulet after the Intelligence constraint is relaxed.
5. Preserve capped elemental resistances and all item/gem requirements after every change.

## Currency

Current balance is **unverified**. Update this before setting hard purchase ceilings.

## Repository map

- [CURRENT_STATUS.md](CURRENT_STATUS.md) — consolidated current audit
- [Constraints.md](Constraints.md) — rules every upgrade must satisfy
- [Attributes.md](Attributes.md) — attribute and resistance dependency budget
- [PassiveTree.md](PassiveTree.md) — passive reassignment options
- [Shopping.md](Shopping.md) — prioritized purchases
- [TradeSearches.md](TradeSearches.md) — reusable trade filters
- [SessionLog.md](SessionLog.md) — chronological progress
- [UpgradeHistory.md](UpgradeHistory.md) — completed changes and measured results
- [WORKFLOW.md](WORKFLOW.md) — how to refresh the tracked build data

## Updating the tracked build data

The repository is the source of truth for our optimization work. After a meaningful character change:

1. Let poe.ninja refresh the public character page; use it as a convenient live reference, not as the authoritative historical record.
2. Export the current character from Path of Building 2 and save the export under `Exports/` with a dated filename such as `Whisperflyte-L93-2026-08-06.txt`.
3. Update `CURRENT_STATUS.md` with the new level, Life, Energy Shield, evasion, DPS, attributes, resistances, Spirit and equipped-item changes.
4. Update `Attributes.md` and `Constraints.md` if requirements, safety margins or resistance dependencies changed.
5. Record completed purchases and before/after deltas in `UpgradeHistory.md` and the dated session summary in `SessionLog.md`.
6. Remove completed priorities from `Shopping.md`, add the next upgrade targets, and update `TradeSearches.md` when the required filters change.
7. Update currency only from a confirmed in-game balance; mark live trade prices and other transient values with the date checked.
8. Commit the refresh in a review branch and merge only after the numbers and gear changes have been verified.

See [WORKFLOW.md](WORKFLOW.md) for the detailed update procedure.

## Operating rule

No item is considered an upgrade until it has been imported into PoB and checked for Life, Energy Shield, evasion, DPS, attributes, resistances, Spirit and lost mechanics.
