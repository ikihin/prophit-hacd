# Review Checklist: PROPHIT

## Formation logic
- [x] Supply matches HACD lots (1,000,000 = 200 × 5,000)
- [x] Stack cost is clear (30 HAC per HACD)
- [x] Participant flow is clear (1-5 HACD → Stack → receive PRT)
- [x] Removal/burn logic defined (burn 5,000 PRT per lot removed)
- [x] Max per participant enforced (5 HACD lots)
- [x] No reserved lots or designated addresses

## Copy safety
- [x] No profit promise
- [x] No misleading backing claim
- [x] No legal guarantee
- [x] No "guaranteed floor" or "risk-free" language
- [x] No investment return language
- [x] Risk disclosure included in launchpad copy
- [x] "Planned" features clearly marked as planned

## Launch readiness
- [ ] Links verified (website, X handle) — Needs issuer confirmation
- [ ] Issuer confirmed numbers — Pending
- [ ] HACD Labs reviewed final parameters — Pending
- [ ] Contact email confirmed — Needs issuer input
- [ ] Target launch date confirmed — Needs issuer confirmation
- [ ] Prediction platform development timeline disclosed — Pending

## JSON validation
- [x] total_supply == total_hacd_lots × units_per_hacd_lot (1,000,000 = 200 × 5,000)
- [x] All required fields present and non-null
- [x] schema_version matches (0.1.0)
- [x] removal_effect specified (burn)
- [x] phase_model specified (public)

## Notes
- Prediction market utility (oracle, resolution, leaderboard) is planned — not promised
- This is a draft package for HACD Labs Incubator Season 2
- Final parameters must be confirmed by the issuer and HACD Labs before Launchpad publication
