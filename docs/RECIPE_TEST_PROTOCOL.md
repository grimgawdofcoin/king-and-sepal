# Recipe test protocol

`RECIPE_NOTES.md` has been a paper formulation since 2026-07-18 — no
kitchen testing has actually happened yet. This is a concrete, runnable
protocol for whenever the founder is ready to test, so "needs kitchen
testing" turns into an actual result instead of staying a permanent
caveat. Nothing here requires spending beyond small quantities of
ingredients already scoped in the budget.

## Test 1 — does it actually dissolve?
The core claim of the product. Test before anything else.
1. Make a small test batch (even a few tablespoons) of the base
   cocoa-butter + lecithin mix from `RECIPE_NOTES.md`, no flavoring yet.
2. Drop a measured piece (e.g. 5g) into 8oz of hot black coffee (~180°F).
3. Time how long until it's visually fully dispersed, and check for any
   floating film or residue after 2 minutes of stirring.
4. Repeat with coffee + milk, and with hot tea, using the same piece size
   and timing method — coffee-creamer literature suggests emulsifiers
   behave differently across these (see `RESEARCH.md`).
5. Try a couple of lecithin ratios within the 0.4–1.4% range to see how
   much is actually needed to hit "no residue," rather than assuming the
   top of the range is required.

**Pass/fail**: no visible film or undissolved residue after 2 minutes of
stirring, across all three drink types, is the bar for "fully dissolve" as
already promised in `BRAND.md`.

## Test 2 — does it hold up as a candy bar?
1. Let a test piece set fully at room temperature.
2. Check texture (snap vs. too soft/waxy) at a normal Florida indoor room
   temp, and after a few hours somewhere warmer (a car, a porch) to
   approximate real shipping/handling conditions.
3. Taste for flavor balance eaten straight, separately from the melt test
   — `RECIPE_NOTES.md` already flags that eat-side and melt-side may pull
   the recipe in different directions; this is where that gets confirmed
   or disproven.

## Test 3 — per-flavor specifics
- **Hazelnut**: since hazelnut paste is fat-heavy, check specifically
  whether it noticeably worsens dissolve behavior vs. the other two
  flavors in Test 1 — this is the flavor most likely to need a recipe
  adjustment (e.g. slightly more lecithin, or less paste).
- **French Vanilla / Caramel**: confirm the flavoring source used (vanilla
  extract brand, caramel flavoring) doesn't introduce dairy unexpectedly —
  affects the allergen line in `LABELS.md`.

## Test 4 — shelf/shipping stability
1. Wrap a finished piece the way it'd actually ship (or just loose, if
   packaging isn't picked yet) and leave it somewhere at Florida ambient
   temperature for a few hours to a day.
2. Check whether it survives without melting/deforming — cocoa butter's
   ~93–101°F melting point means this is a real risk, not a formality (see
   `PACKAGING.md`'s shipping-heat section).

## What to record
For each test: piece size, lecithin %, drink type (if applicable),
dissolve time, pass/fail on residue, and taste/texture notes. Even a rough
running note in a new `docs/journal/` entry or a simple table added back
into `RECIPE_NOTES.md` would let future research passes stop treating the
recipe as untested paper math.

## What this doesn't replace
This is a kitchen-scale sanity check, not food-safety validation. It
doesn't substitute for whatever labeling/allergen accuracy is needed before
real sales (`LABELS.md`), and it isn't a substitute for professional
recipe/food-science review if the founder wants one before scaling past
the hand-sell phase.
