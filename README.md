# PROPHIT (PRT)

**Predict. Stake. Prove it. Formed through HACD.**

PROPHIT is a prediction market Stack Asset formed through [HACD Stack](https://hacd.it). Holders use PRT to stake on market predictions, earn from accuracy, and build on-chain reputation backed by real PoW formation cost.

> Bitcoin proved PoW for money. HACD brings PoW to assets. PROPHIT brings PoW to predictions.

## Overview

| Parameter | Value |
|-----------|-------|
| Ticker | PRT |
| Type | Fungible Token (FT) |
| Total Supply | 1,000,000 PRT |
| HACD Lots | 200 |
| PRT per Lot | 5,000 |
| Stack Cost | 30 HAC per HACD |
| Max per Participant | 5 lots (25,000 PRT) |
| Phase Model | Public (all lots open) |
| Removal Effect | Burn (permanent) |
| Team Allocation | None |

## How It Works

1. **Form** — Stack your HACD with 30 HAC to form 5,000 PRT per lot
2. **Predict** — Stake PRT on market predictions (price calls, event outcomes)
3. **Earn** — Correct predictions earn PRT from incorrect stakers
4. **Prove** — Build a verifiable on-chain track record over time

## Why HACD?

Prediction markets need skin in the game. HACD Stack provides:

- **Real formation cost** — No free mints, no airdrops, no inflation
- **Fixed supply** — 1M PRT max, deflationary through burns
- **Transparent provenance** — Every token traces to a HACD formation event
- **Burn mechanism** — Unstacking destroys PRT permanently

## Project Structure

```
prophit-launch/
├── docs/
│   ├── index.html          # Landing page (GitHub Pages)
│   └── CNAME               # Custom domain config
├── incubator_fit_review.md # HACD fit assessment
├── project_profile.md      # Project overview
├── stack_design.md         # Token formation design
├── launch_spec.json        # Machine-readable spec (validated)
├── launchpad_copy.md       # Launchpad page copy
├── issuer_faq.md           # Participant FAQ
├── x_announcement.md       # Social media drafts
└── review_checklist.md     # Pre-launch checklist
```

## Links

- Website: [prophit.biz.id](https://prophit.biz.id)
- Incubator: [HACD Labs Incubator Season 2](https://growstreams.xyz/app/projects/HACD)
- Issuance Skill: [HACD AI Issuance Skill](https://github.com/Satyam-10124/hacd-incubator-ai-issuance-skill)

## Validation

The `launch_spec.json` has been validated using the HACD Issuance Skill validator:

```bash
python3 scripts/validate_launch_spec.py launch_spec.json
# OK: launch spec passed validation
# Formation cost reference: 6,000 HAC + network fees
```

## Status

This is a **draft** issuance package for HACD Labs Incubator Season 2. Final parameters must be confirmed by the issuer and HACD Labs before Launchpad publication.

## Disclaimer

PRT is a utility Stack Asset for prediction market participation, not an investment product. No price, liquidity, listing, or return is guaranteed. Prediction market features depend on platform development. Formation cost is non-refundable. Not financial advice.

---

Built for [HACD Labs Incubator Season 2](https://growstreams.xyz/app/projects/HACD) | Powered by [HACD Stack](https://hacd.it)
