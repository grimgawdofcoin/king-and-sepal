# Legal formation checklist (Florida)

Turns the one-line "legal formation" phase in `BUSINESS_PLAN.md` into an
actual sequence, so once the founder gives the go-ahead this is execution,
not research. **Nothing here has been filed or paid for — every step below
still needs explicit founder sign-off before any money moves or any form
gets submitted**, per the guardrails in `OPEN_QUESTIONS.md`.

## 1. LLC name check + reservation
- Search "King & Sepal LLC" (and "King and Sepal LLC") against Florida's
  Division of Corporations name database before filing — a duplicate name
  gets the filing rejected. Attempted to check this automatically; Sunbiz's
  search returned an HTTP 403 to automated fetch, same as the USPTO
  trademark search — this needs a human to actually run the search at
  https://search.sunbiz.org/Inquiry/CorporationSearch/ByName.
- Note: this is a *state name registry* check, separate from the *federal
  trademark* check in `OPEN_QUESTIONS.md` — passing one doesn't mean the
  other is clear. Both are still outstanding.

## 2. Registered agent
- Needs a named individual or entity with a physical Florida street address
  (no P.O. boxes), 18+. Can be the founder if they have a FL address, or a
  commercial registered-agent service.
- **Open question**: who/what will this be? Not yet decided.

## 3. File Articles of Organization
- Filed online via Sunbiz (efile.sunbiz.org/llc_file.html). Needs: LLC
  legal name, registered agent info, principal office address, member/
  manager names and addresses.
- Cost: $100 state filing fee + $25 registered agent designation fee =
  **$125 total**, matches the existing budget line in `BUSINESS_PLAN.md`.
- Processing: ~1–2 business days online (up to 5 in busy periods).

## 4. EIN (federal tax ID)
- Free, direct from the IRS (irs.gov) — not a paid service, watch for
  third-party sites that charge for this. Needed to open a business bank
  account even without employees.

## 5. Local Business Tax Receipt — Broward vs. Miami-Dade (2026-07-21)
Founder narrowed this to Broward and/or Miami-Dade. These two counties
have meaningfully different requirements, so here's both — **still need
one final answer: which single county is the actual home-kitchen address
in?** A cottage food operation has one physical location; it can't be
registered in two counties at once, though selling to customers in both is
fine under cottage food law (in-state sales aren't restricted by county).

**Broward County:**
- Every business, including home-based one-person operations, needs a
  Broward Local Business Tax Receipt (some exemptions exist, unlikely to
  apply here).
- Fee: **$27–$150** depending on business type/category.
- Valid Oct 1–Sep 30, renews annually.
- No separate Certificate of Use required for home-based businesses at the
  *county* level. If the address is inside a city (vs. unincorporated
  county), that city may have its own additional business tax receipt,
  zoning, home occupation, or sign rules — check the specific city.
- Source: https://browardtax.org/faqs/local-business-tax/,
  https://www.broward.org/RecordsTaxesTreasury/taxcollector/Pages/LocalBusinessTaxes.aspx.

**Miami-Dade County:**
- Requires a **Home Occupation Permit (HOP)** from the Department of
  Regulatory and Economic Resources *before* the Business Tax Receipt —
  needs a floor plan of the residence showing the home office/kitchen
  location and dimensions, plus a home occupation affidavit.
  This is a materially bigger paperwork lift than Broward's process.
- Businesses in **unincorporated** Miami-Dade also need a separate
  Certificate of Use and Occupancy on top of the Business Tax Receipt.
- Apply/pay via https://miamidade.county-taxes.com/btexpress or
  (305) 279-4949.
- Source: https://mdctaxcollector.gov/services/local-business-tax-receipt,
  https://www.cutlerbay-fl.gov/finance/faq/what-documents-must-i-provide-my-home-based-business-order-obtain-local-business-tax.

**Bottom line**: if there's a real choice between the two (e.g. the
founder could set up the home kitchen in either county), Broward is
simpler and cheaper to get licensed in — no separate Home Occupation
Permit/floor-plan/affidavit requirement at the county level, unlike
Miami-Dade. If the home kitchen's address is fixed already, that answer
determines which process applies, not a preference.

## 6. Home occupation permit — general FL context
Florida Statute § 559.955 broadly protects home-based businesses statewide
and blocks cities/counties from requiring a separate food license or
inspecting the home kitchen (cottage food law already covers that). But as
shown above, Miami-Dade requires a formal Home Occupation Permit process
regardless; Broward's home occupation rules mostly show up at the *city*
level (if inside city limits) rather than the county level. Source:
Fla. Stat. § 559.955
(https://www.leg.state.fl.us/statutes/index.cfm?App_mode=Display_Statute&URL=0500-0599%2F0559%2FSections%2F0559.955.html),
https://legalclarity.org/how-to-get-a-home-occupation-permit-in-florida/.

## 7. Cottage food — confirmed, no separate step needed
Re-confirmed: Florida cottage food operations do **not** need to register
with FDACS or get a permit — Fla. Stat. § 500.80 exempts qualifying
operations from permitting/inspection entirely. (One source found earlier
claimed FDACS registration is mandatory; the official FDACS site and the
majority of other sources contradict that, so treating "no registration
required" as correct.) Source: https://www.fdacs.gov/Business-Services/Food-Establishments/Cottage-Foods.
Labeling and sales-channel rules (already in `BUSINESS_PLAN.md`) still
apply regardless.

## Sequence summary
1. Name check (needs a human — automated check blocked)
2. Pick registered agent
3. File Articles of Organization ($125)
4. Get EIN (free)
5. Business Tax Receipt — Broward ($27–150, no extra HOP at county level)
   or Miami-Dade ($27–150 range likely similar + mandatory Home Occupation
   Permit with floor plan/affidavit, + Certificate of Use if unincorporated)
6. Home occupation permit — folded into step 5 for Miami-Dade; check the
   specific city's rules if the Broward address is inside city limits
7. Cottage food: no action needed, just follow labeling rules

Only remaining blocker on steps 5/6: **which single county** (Broward or
Miami-Dade) is the actual home-kitchen address in.
