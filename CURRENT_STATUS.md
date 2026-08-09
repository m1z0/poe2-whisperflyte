# Whisperflyte — Current Build Status

Last updated: 2026-08-08

## Character snapshot

- Character: **Whisperflyte**
- Level: **94**
- Class: **Ranger**
- Ascendancy: **Deadeye**
- League: **Runes of Aldur**
- Profile: `BatseBayan-2892`
- Latest PoB: `Exports/Whisperflyte-L94-2026-08-08.txt`

| Stat | Current | Requirement / target | Margin / note |
|---|---:|---:|---|
| Strength | 58 | 45 required | +13 |
| Dexterity | 191 | 163 required | +28 |
| Intelligence | 117 | 115 required | **+2** |
| Life | 1,768 | 1,850–2,000 target | Improved, still below target |
| Energy Shield | 1,129 | Maintain 1,100+ | On target |
| Evasion | 17,427 | Maintain 17,000+ | On target |
| Fire Resistance | 75% | 75% minimum | +6 overcap |
| Cold Resistance | 75% | 75% minimum | +15 overcap |
| Lightning Resistance | 75% | 75% minimum | +12 overcap |
| Chaos Resistance | 21% | 35–50% target | Still low |
| Spirit | 148 | Preserve current setup | 33 unreserved |
| Combined PoB DPS | ~39,220 | Baseline | Re-evaluate per candidate |

## Changes since 2026-08-06 baseline

| Metric | Previous | Current | Net change |
|---|---:|---:|---:|
| Level | 93 | 94 | +1 |
| Life | 1,674 | 1,768 | +94 |
| Energy Shield | 1,129 | 1,129 | 0 |
| Evasion | 17,427 | 17,427 | 0 |
| Strength | 78 | 58 | -20 |
| Dexterity | 171 | 191 | +20 |
| Intelligence | 117 | 117 | 0 |
| Fire overcap | below cap | +6 | Improved |
| Cold overcap | +8 | +15 | +7 |
| Lightning overcap | +5 | +12 | +7 |
| Chaos Resistance | 17% | 21% | +4 |
| Combined PoB DPS | ~41,220 | ~39,220 | ~-2,000 |

The export proves the net stat changes above. It does **not** by itself prove which exact passive nodes caused the Strength/Dexterity shift, so the database does not infer that detail.

## Current gear audit

| Slot | Current item | Status |
|---|---|---|
| Bow | Phoenix Thirst | Hold until later |
| Quiver | Cadiro's Gambit | Build-defining; hold |
| Helmet | Grim Corona | Attribute/resistance anchor |
| Body Armour | Storm Coat | Strong; hold |
| Gloves | Brood Nails | Medium-priority future upgrade |
| Boots | Storm Goad | Attribute anchor; later |
| Belt | Torment Buckle | Strong defensive upgrade candidate |
| Amulet | Carrion Gorget | **Current high-impact target** |
| Ring 1 | Golem Knot | **Upgrade completed** |
| Ring 2 | Dusk Spiral | Medium-priority future upgrade |

## Golem Knot — current Ring 1

**Prismatic Ring, item level 82**

- +7% to all Elemental Resistances
- Adds 11–19 Physical Damage to Attacks
- Adds 21–32 Cold Damage to Attacks
- +118 maximum Life
- +21% Chaos Resistance
- 13.4 Life Regeneration per second
- Leech 6.16% of Physical Attack Damage as Mana

This replaced `Bramble Loop`. Purchase price is not recorded yet.

## Current constraints

Every proposed upgrade must preserve:

- all current item and gem requirements
- capped fire, cold and lightning resistance
- enough Spirit for the persistent-skill setup
- 35% movement speed when replacing boots unless the total upgrade is exceptional
- the current bow and Cadiro's Gambit mechanics unless PoB proves a replacement is superior
- approximately 17,000+ evasion and 1,100+ Energy Shield

Preferred attribute safety margins:

- Strength: at least +10 over requirement
- Dexterity: at least +10 over requirement
- Intelligence: at least +10 to +15 over requirement

**Current concern:** Intelligence remains only +2 above requirement, so an amulet replacement must either retain enough Intelligence or be paired with a verified passive/gear adjustment.

## Active upgrade plan

### U001 — Replace Bramble Loop

**Status: Completed** — replaced by `Golem Knot`.

### U004 — Upgrade Carrion Gorget

**Status: Active search**

Current amulet provides:

- Allocates Serrated Edges
- 48 total Spirit (11 implicit + 37 explicit)
- +14 Intelligence
- +34% Fire Resistance
- +30% Cold Resistance
- +26 maximum Life
- 28% increased Evasion Rating

Target profile discussed on 2026-08-08:

- Allocates Serrated Edges
- ~50 Spirit
- +2 to Level of All Projectile Skills
- strong Critical Damage Bonus
- +15% or better to all Elemental Resistances
- useful Energy Shield / global Armour-Evasion-ES scaling
- enough Intelligence elsewhere to keep the build legal

The pictured reference amulet also had 44% increased maximum Energy Shield, +50 Spirit, 25% increased global Armour/Evasion/ES, 34% increased Critical Damage Bonus, +2 projectile skill levels and +15% all elemental resistances.

### U002 — Upgrade Torment Buckle

Still a strong defensive follow-up, especially for more Life/Chaos resistance while retaining three charm slots.

### U003 — Passive attribute rebalance

Do **not** make further attribute changes blindly. The latest export has 58 Str / 191 Dex / 117 Int; exact passive-node changes should be verified before the next respec. Intelligence is still the limiting attribute.

## Validation process

Before buying an item, record listing URL, price and item text, import it into PoB, and compare Life, ES, evasion, DPS, Strength/Dexterity/Intelligence, elemental/chaos resistances, Spirit and lost utility. No item is considered an upgrade until it passes these checks.
