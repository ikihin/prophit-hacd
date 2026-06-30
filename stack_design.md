# Stack Design: PROPHIT

## Asset type

FT (Fungible Token)

## Supply

- Total supply: 1,000,000 PRT
- HACD lots: 200
- Units per HACD: 5,000 PRT
- All lots are equal: Yes

Supply formula check:

```
total_supply = total_hacd_lots × units_per_hacd_lot
1,000,000 = 200 × 5,000 ✓
```

## Stack cost

- Cost per HACD: 30 HAC
- Estimated total formation cost reference: 6,000 HAC (200 × 30 HAC)
- Network fee: standard Hacash transaction fee per lot (paid by participant)
- Formation cost reference is an on-chain cost input, not a guaranteed price floor.

## Formation rules

1. Each participant must hold at least 1 HACD and enough HAC to cover 30 HAC stack cost plus network fee.
2. Each participant may Stack between 1 and 5 HACD lots per the launch rules.
3. Each Stack transaction on 1 HACD lot produces exactly 5,000 PRT.
4. All 200 lots follow identical rules. No tiers, no reserved lots, no designated address requirement.
5. Once all 200 lots are Stacked, no more PRT can be formed. Supply is permanently fixed.

## Participant flow

1. Prepare 1–5 HACD units.
2. Prepare enough HAC: (number of HACD) × 30 HAC + estimated network fee.
3. Go to HACD Launchpad and find PROPHIT (PRT).
4. Enter HACD name(s) and confirm Stack transaction.
5. Verify formed PRT balance on Launchpad or Hacash explorer.

## Removal / burn logic

If a participant removes the Stack from a HACD lot, the 5,000 PRT tied to that lot are burned. The HACD is released but the PRT units are permanently destroyed. Stack cost HAC is not refunded. This mechanism ensures HACD containers and PRT supply stay linked as long as the Stack is active.
