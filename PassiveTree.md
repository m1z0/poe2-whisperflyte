# Passive Tree Plan

Snapshot date: **2026-08-08**

## Current observed attribute state

Latest PoB reports:

- Strength: **58** (45 required, +13 spare)
- Dexterity: **191** (163 required, +28 spare)
- Intelligence: **117** (115 required, +2 spare)

Compared with the 2026-08-06 baseline, this is a net change of **-20 Strength / +20 Dexterity / 0 Intelligence**. The current export proves the totals but does not identify which exact passive nodes were changed, so this file does not infer the node-by-node respec history.

## Immediate recommendation

**Do not make another passive attribute change yet.**

The next target is the amulet, and Carrion Gorget currently provides +14 Intelligence. Intelligence is already only +2 above requirement, so the exact amulet candidate should determine whether passive points need to move into Intelligence.

## Strength-to-Intelligence tradeoff

Where a flexible attribute node can be reassigned, changing 5 Strength to Intelligence costs approximately 10 maximum Life from the lost Strength.

| Nodes changed | Strength lost | Intelligence gained | Approximate Life lost |
|---:|---:|---:|---:|
| 1 | 5 | 5 | 10 |
| 2 | 10 | 10 | 20 |

With only +13 Strength spare today, more than two additional Strength-to-Intelligence changes would put Strength at or below the preferred +10 safety margin unless another item adds Strength.

## Decision rule for the next amulet

1. Import the candidate amulet into PoB.
2. Check final Intelligence and Strength requirements.
3. If Intelligence is short, first compare the cost of getting Intelligence on the amulet/another item versus one or two flexible passive reassignments.
4. Preserve at least 55 Strength when practical and at least 125–130 Intelligence after the change.
5. Recheck Life, resistances, Spirit and DPS before committing the respec.

The previous four-node Strength-to-Intelligence proposal is no longer the active recommendation because the current character already sits at 58 Strength.
