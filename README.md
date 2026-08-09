# Whisperflyte Build Tracker

Personal optimization journal for **Whisperflyte**, a level 94 Deadeye in the Runes of Aldur league.

## Character links

- [Whisperflyte on poe.ninja](https://poe.ninja/poe2/profile/BatseBayan-2892/runesofaldur/character/Whisperflyte)

## Current snapshot

PoB snapshot: **2026-08-08**

| Metric | Current | Near-term target |
|---|---:|---:|
| Life | 1,768 | 1,850–2,000 |
| Energy Shield | 1,129 | Maintain 1,100+ |
| Evasion | 17,427 | Maintain 17,000+ |
| Fire Resistance | 75% (+6 overcap) | 15%+ overcap |
| Cold Resistance | 75% (+15 overcap) | 15%+ overcap |
| Lightning Resistance | 75% (+12 overcap) | 15%+ overcap |
| Chaos Resistance | 21% | 35–50% |
| Strength | 58 / 45 required | +10 margin minimum |
| Dexterity | 191 / 163 required | Healthy margin |
| Intelligence | 117 / 115 required | **Only +2 margin** |
| Spirit | 148 / 33 unreserved | Preserve current skills |
| Combined PoB DPS | ~39,220 | Track after each upgrade |

## Current objective

1. **Ring upgrade complete:** `Golem Knot` replaced `Bramble Loop`.
2. Find a high-impact **Carrion Gorget amulet replacement** while preserving Spirit, elemental resistances and Intelligence requirements.
3. Improve Chaos resistance toward 35–50%.
4. Improve Life toward 1,850–2,000 without giving up the current evasion/ES floor.
5. Re-evaluate the belt and remaining jewellery after the amulet decision.

## Currency

User-reported balance is approximately **20 Divine Orbs** as of 2026-08-08; exact balance and Exalted count are not confirmed.

## Repository map

- [CURRENT_STATUS.md](CURRENT_STATUS.md) — consolidated current audit
- [Constraints.md](Constraints.md) — rules every upgrade must satisfy
- [Attributes.md](Attributes.md) — attribute and resistance dependency budget
- [PassiveTree.md](PassiveTree.md) — passive reassignment options
- [Shopping.md](Shopping.md) — prioritized purchases
- [TradeSearches.md](TradeSearches.md) — reusable trade filters
- [Currency.md](Currency.md) — current budget and spending log
- [SessionLog.md](SessionLog.md) — chronological progress
- [UpgradeHistory.md](UpgradeHistory.md) — completed changes and measured results
- [WORKFLOW.md](WORKFLOW.md) — how to refresh the tracked build data
- [Exports/](Exports/) — dated raw PoB exports

## Updating the tracked build data

The repository is the source of truth for our optimization work. After a meaningful character change, save a dated PoB export, refresh the current stats/dependencies, record completed upgrades and costs, then update the active shopping plan. See [WORKFLOW.md](WORKFLOW.md) for the full procedure.

## Operating rule

No item is considered an upgrade until it has been imported into PoB and checked for Life, Energy Shield, evasion, DPS, attributes, resistances, Spirit and lost mechanics.
