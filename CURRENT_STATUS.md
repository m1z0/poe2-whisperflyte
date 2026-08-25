# Whisperflyte — Current Build Status

Last updated: 2026-08-24

## Character snapshot

- Character: **Whisperflyte**
- Level: **95**
- Class: **Ranger**
- Ascendancy: **Deadeye**
- League: **Runes of Aldur**
- Profile: `BatseBayan-2892`
- Latest PoB: `Exports/Whisperflyte-L95-2026-08-24.txt`

| Stat | Current | Requirement / target | Margin / note |
|---|---:|---:|---|
| Strength | 58 | 45 required | +13 |
| Dexterity | 191 | 163 required | +28 |
| Intelligence | 117 | 115 required | **+2** |
| Life | 1,781 | 1,850–2,000 target | +13 vs 2026-08-08 |
| Energy Shield | 1,129 | Maintain 1,100+ | On target |
| Evasion | 14,327 | Rebuild toward 17,000+ | **-3,100 vs 2026-08-08** |
| Evade Chance | 60% | Improve | Lower than prior snapshot |
| Deflection Rating | 16,046 | Maintain | Strong |
| Deflect Chance | 72% | Maintain | Strong |
| Armour | 278 | — | Negligible |
| Physical Damage Reduction | 3% | — | Low |
| Fire Resistance | 75% | 75% minimum | +6 overcap |
| Cold Resistance | 75% | 75% minimum | +15 overcap |
| Lightning Resistance | 75% | 75% minimum | +12 overcap |
| Chaos Resistance | 21% | 35–50% target | Still low |
| Mana | 822 | — | — |
| Mana Regeneration | 60.8/sec | Sustain normal attacks | Improved by jewel support |
| Spirit | 148 | Preserve current setup | 33 unreserved |
| Total EHP | ~23,895 | Improve | Current PoB value |
| Physical Max Hit | 3,413 | Improve | Main defensive weakness |
| Elemental Max Hit | 11,650 | Maintain/improve | Fire/Cold/Lightning |
| Chaos Max Hit | 3,415 | Improve | Tracks low Chaos res |
| Combined PoB DPS | Unavailable | — | Export currently calculates 0 for selected main group |

## Changes since 2026-08-08 snapshot

| Metric | 2026-08-08 | 2026-08-24 | Net change |
|---|---:|---:|---:|
| Level | 94 | 95 | +1 |
| Life | 1,768 | 1,781 | +13 |
| Energy Shield | 1,129 | 1,129 | 0 |
| Evasion | 17,427 | 14,327 | **-3,100 (-17.8%)** |
| Strength | 58 | 58 | 0 |
| Dexterity | 191 | 191 | 0 |
| Intelligence | 117 | 117 | 0 |
| Fire overcap | +6 | +6 | 0 |
| Cold overcap | +15 | +15 | 0 |
| Lightning overcap | +12 | +12 | 0 |
| Chaos Resistance | 21% | 21% | 0 |
| Spirit | 148 / 33 free | 148 / 33 free | 0 |

The latest export does not provide a comparable DPS value because its selected main calculation group (`Mirage Deadeye` / Ice Shot cooldown group) reports zero damage. Do not interpret the zero as a real DPS loss.

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
| Ring 1 | Golem Knot | Keep |
| Ring 2 | Dusk Spiral | Medium-priority future upgrade |

## Jewel audit

### Heart of the Well — Diamond

- Gain 11% of Damage as Extra Cold Damage
- Gain 8% of Damage as Extra Chaos Damage
- 4% increased chance to inflict Ailments
- Damaging Ailments deal damage 4% faster

**Assessment:** strong offensive jewel; keep.

### Foe Hope — Emerald

- 20% increased Evasion Rating
- 5% increased Flask Effect Duration
- 2% increased Attack Speed
- 9% increased Projectile Damage

**Assessment:** efficient hybrid defense/offense jewel; keep for now.

### Rapture Creed — Sapphire

- 5% increased Cold Damage
- 15% increased Mana Regeneration Rate
- Recover 2% of maximum Mana on Kill
- 14% increased Magnitude of Damaging Ailments inflicted with Critical Hits

**Assessment:** useful mana-sustain stopgap. The 15% mana regeneration directly addresses the mild sustain issue, and 2% maximum Mana on Kill is useful while mapping. The remaining affixes are only modestly offensive, so this is not a long-term premium jewel. Replace later only when a jewel with comparable mana sustain plus stronger attack/projectile/critical scaling is available at good value.

## Mana sustain

Current relevant sources:

- 822 maximum Mana
- 60.8 Mana regenerated per second in the latest PoB
- `Golem Knot`: leeches 6.16% of Physical Attack Damage as Mana
- `Rapture Creed`: 15% increased Mana Regeneration Rate and 2% maximum Mana recovered on Kill
- `Lavianga's Spirits` remains equipped

**Conclusion:** mana sustain should now be adequate for the previously described mild deficit. Do not spend significant currency solving mana unless actual gameplay still shows starvation during sustained single-target attacks.

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
- approximately 1,100+ Energy Shield
- mana sustain at least as good as the current setup

Preferred attribute safety margins:

- Strength: at least +10 over requirement
- Dexterity: at least +10 over requirement
- Intelligence: at least +10 to +15 over requirement

**Current concerns:**

1. Intelligence remains only +2 above requirement.
2. Evasion has fallen to 14,327 from 17,427 in the prior snapshot.
3. Chaos resistance remains only 21%.
4. Physical max hit remains much weaker than elemental max hit.

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

Target profile:

- Allocates Serrated Edges
- about 50 Spirit
- +2 to Level of All Projectile Skills
- strong Critical Damage Bonus
- useful all-elemental resistance
- useful Energy Shield / global Armour-Evasion-ES scaling
- enough Intelligence elsewhere to keep the build legal

Because current Intelligence is still only +2 over requirement, a no-Intelligence amulet requires a verified passive or gear compensation.

### U002 — Upgrade Torment Buckle

Still a strong defensive follow-up, particularly if it adds more Life and Chaos resistance while retaining three charm slots.

### U003 — Passive attribute rebalance

Do **not** make further blind attribute changes. Current attributes remain 58 Str / 191 Dex / 117 Int. Intelligence is still the limiting attribute.

### U009 — Improve Rapture Creed later

Only after the more important amulet/defensive upgrades. Desired replacement: retain enough mana regeneration to keep sustain comfortable, then add two or more strong offensive modifiers such as projectile damage, bow/attack damage, attack speed, quiver scaling, or critical scaling.

## Validation process

Before buying an item, record listing URL, price and item text, import it into PoB, and compare Life, ES, evasion, DPS, Strength/Dexterity/Intelligence, elemental/chaos resistances, Spirit, mana sustain and lost utility. No item is considered an upgrade until it passes these checks.
