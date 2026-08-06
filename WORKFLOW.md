# Workflow

This repository is the source of truth for future Whisperflyte optimization sessions.

Public character reference:

- [Whisperflyte on poe.ninja](https://poe.ninja/poe2/profile/BatseBayan-2892/runesofaldur/character/Whisperflyte)

poe.ninja is useful as a live public reference, but this repository is the historical database for our decisions, snapshots, purchases and measured build changes.

## When to refresh the database

Refresh the tracked data after any meaningful change, including:

- equipping or replacing an item
- changing passive-tree allocations
- changing gems or persistent skills
- gaining a level that changes requirements or stats
- changing Spirit usage
- changing charms, flasks or build-defining mechanics
- making a purchase that changes the active shopping plan

A fresh poe.ninja snapshot alone is not sufficient because it does not preserve our prior state, cost basis or upgrade reasoning.

## Database refresh procedure

1. **Capture the authoritative build state.**
   - Export the current character from Path of Building 2.
   - Save the raw export under `Exports/` using a dated filename such as `Whisperflyte-L93-2026-08-06.txt`.
   - Do not overwrite older exports.

2. **Refresh the character snapshot.**
   - Update `CURRENT_STATUS.md` with the current level, Life, Energy Shield, evasion, DPS, attributes, elemental resistances, chaos resistance, Spirit and equipped gear.
   - Update the `Last updated` date.

3. **Recalculate dependencies.**
   - Update `Attributes.md` if Strength, Dexterity or Intelligence requirements or item contributions changed.
   - Recalculate resistance headroom after any gear swap.
   - Update `Constraints.md` if the minimum safe margins, movement-speed requirement, Spirit requirement or defensive floors have changed.

4. **Record completed changes.**
   - Add purchases and respecs to `UpgradeHistory.md`.
   - Record price, replaced item, and measured before/after changes for Life, Energy Shield, evasion, DPS, attributes, resistances and Spirit.
   - Add a dated summary to `SessionLog.md`.

5. **Rebuild the active plan.**
   - Mark completed items in `Shopping.md` and remove them from the active queue when appropriate.
   - Re-rank the remaining upgrades by impact, cost and dependency risk.
   - Update `TradeSearches.md` whenever the required affixes or budgets change.

6. **Refresh currency and market data.**
   - Update `Currency.md` only from a confirmed in-game balance.
   - Date any live trade-price observations because market prices are transient.
   - Never carry an old price forward as if it were current.

7. **Validate before merging.**
   - Import candidate equipment into PoB before treating it as an upgrade.
   - Confirm all item and gem requirements remain satisfied.
   - Confirm fire, cold and lightning resistance remain capped.
   - Confirm Spirit and movement-speed constraints are preserved.
   - Check for lost build mechanics, not only DPS changes.

8. **Commit through a review branch.**
   - Create an `agent/...` branch for the refresh.
   - Commit the documentation changes there.
   - Review the GitHub diff.
   - Merge only after the numbers and item changes match the actual character.

## Routine after each meaningful build change

At minimum:

1. Save a dated PoB export.
2. Update the current stats and constraints.
3. Record the purchase and measured deltas in `UpgradeHistory.md`.
4. Update `Shopping.md` so only active priorities remain open.
5. Add a dated entry to `SessionLog.md`.

Unverified values, especially currency and live trade prices, must be labeled as such rather than treated as authoritative.
