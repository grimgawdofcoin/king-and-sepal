# Unit economics — first-pass model

Synthesizes `RECIPE_NOTES.md`, `PRICING.md`, `PACKAGING.md`, and
`BUSINESS_PLAN.md` into an actual per-bar cost estimate, to sanity-check
whether the recipe + pricing + budget combination is viable. **Every
number here is a placeholder or estimate — nothing is a confirmed
quote.** The point is to catch a math problem now rather than after
spending the budget, not to be precise.

## Working assumption: net weight
`LABELS.md` left net weight undecided. For this model, assuming **1.5 oz
(~42g) per bar** — a common single-serving candy bar size — purely as a
working number to make the math concrete. Not a decision; revisit once
the founder picks an actual target weight.

## Raw ingredient cost, per bar (assuming 42g, per `RECIPE_NOTES.md` ratios)
Using wholesale prices found via web search (not confirmed quotes):
cocoa butter/cocoa mass ~$3/lb, sunflower lecithin ~$3.74/lb (sources:
https://www.selinawamucii.com/insights/prices/united-states-of-america/cocoa-butter/,
https://velonainc.com/product/sunflower-lecithin-wholesale/).

| Component | ~% of bar | ~grams | Est. cost |
|---|---|---|---|
| Cocoa butter/solids | 65% | 27.3g | ~$0.18 |
| Sweetener | 25% | 10.5g | ~$0.01 (bulk sugar is cheap, ~$0.60/lb) |
| Lecithin | 1% | 0.4g | ~$0.003 |
| Flavoring (vanilla/caramel/hazelnut) | ~9% | 3.8g | ~$0.10–0.30 (rough — hazelnut paste likely costliest) |
| **Raw ingredient total** | | | **~$0.30–0.50/bar** |

This is in line with candy generally — ingredient cost is usually a small
fraction of retail price; packaging and labor dominate the real cost.

## Packaging + labeling, per bar
- No-MOQ kraft box (`PACKAGING.md`): no real quote yet, but small-run
  custom kraft boxes typically run roughly **$0.75–1.50/unit** at low
  volume — placeholder, needs an actual quote from one of the four
  suppliers found.
- Printed label: ~$0.05–0.15/unit if done via a home printer or basic
  print-on-demand service.

## Rough all-in cost per bar
**~$1.10–2.15/bar** (ingredients + packaging + label), before accounting
for the founder's own labor time, which isn't priced in here at all.

## Margin check against the $7–11 working price
At $7/bar (low end): gross margin ≈ $4.85–5.90/bar (~70–84%).
At $11/bar (high end): gross margin ≈ $8.85–9.90/bar (~80–90%).
**This part of the math works** — healthy gross margin per unit,
consistent with how candy/craft chocolate is priced generally.

## The part that doesn't automatically work: recovering the $500 setup budget from the hand-sell phase
This is the actual finding worth flagging. The ~$500 budget (LLC, annual
report, business tax receipt, and whatever else gets spent before Drop 01)
is a **fixed cost**, separate from per-bar cost. Hand-selling 30–50 units
at $7–11/bar generates **$210–550 in revenue** — which is roughly the same
size as the setup budget itself, *before* subtracting per-bar ingredient/
packaging costs.

**In plain terms: the hand-sell phase, by itself, will likely not fully
pay back the setup costs, even though each individual bar is priced at a
healthy margin.** This is normal for a first batch of any new food
business — fixed costs are meant to amortize across many future
drops, not get recovered in the very first 30–50 units — but it's worth
the founder knowing this going in, so the hand-sell phase is understood as
a **validation/feedback exercise**, not a break-even milestone. Drop 01
and the ongoing drop cadence are where the fixed costs actually start
getting recovered, assuming the hand-sell phase validates the product.

## What would sharpen this model
- A real cacao/cocoa-butter quote (outreach currently paused — see
  `OPEN_QUESTIONS.md`).
- A real packaging quote from one of the no-MOQ suppliers in `PACKAGING.md`.
- An actual decided net weight (currently just this doc's working
  assumption).
- Real recipe testing (`RECIPE_TEST_PROTOCOL.md`) — flavoring costs in
  particular are the roughest estimate here.
