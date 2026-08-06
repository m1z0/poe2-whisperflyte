# Passive Tree Plan

## Objective

Improve baseline attribute balance without unnecessarily sacrificing Life or core damage/defensive passives.

## Strength-to-Intelligence tradeoff

Reassigning 5 Strength to Intelligence costs approximately 10 maximum Life.

| Nodes changed | Strength lost | Intelligence gained | Approximate Life lost |
|---:|---:|---:|---:|
| 1 | 5 | 5 | 10 |
| 2 | 10 | 10 | 20 |
| 3 | 15 | 15 | 30 |
| 4 | 20 | 20 | 40 |
| 6 | 30 | 30 | 60 |

## Recommended starting ceiling

A four-node balanced reassignment would produce approximately:

| Attribute | Before | After | Requirement | Margin after |
|---|---:|---:|---:|---:|
| Strength | 78 | 58 | 45 | +13 |
| Dexterity | 171 | 171 | 163 | +8 |
| Intelligence | 117 | 137 | 115 | +22 |
| Life | 1,674 | ~1,634 | — | -40 |

This is a ceiling, not an automatic first step.

## Preferred sequencing

1. Find a Bramble Loop replacement.
2. Import the candidate into PoB.
3. Check whether the ring adds Intelligence.
4. Apply only the number of Strength-to-Intelligence changes needed to maintain a safe buffer.
5. Recheck Life, attributes, resistances and DPS.

## Decision rule

- Ring adds 20+ Intelligence: passive reassignment may be unnecessary.
- Ring adds 10–19 Intelligence: consider one or two node changes.
- Ring adds no Intelligence: consider three or four node changes.
- Never reduce Strength to the exact requirement.
- Avoid reducing Dexterity while the current margin is only +8.
