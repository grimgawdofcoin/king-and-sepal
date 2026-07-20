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

## 5. Local Business Tax Receipt — needs the county first
- Issued at the **county** level (and separately at the **city** level if
  the business address is inside city limits) — not a single statewide
  process. The $50–150 estimate in `BUSINESS_PLAN.md` is a rough range
  across counties, not a specific number.
- **Open question, new**: which Florida county (and city, if applicable)
  is the business actually based in? Can't look up the real fee or
  application steps without this.
- Typical requirements to apply: Sunbiz registration (so this comes after
  step 3), zoning approval, sometimes an EIN or SSN.

## 6. Home occupation permit — separate from the Business Tax Receipt
- Florida Statute § 559.955 broadly protects home-based businesses
  statewide and blocks cities/counties from requiring a separate food
  license or inspecting the home kitchen (cottage food law already covers
  that). But most FL cities/counties still require a **home occupation
  permit** confirming the business is compatible with residential zoning,
  and specifics vary a lot — e.g. some cities restrict storing/selling
  merchandise from the property. This has **not been checked** for the
  founder's specific city/county yet — same blocker as step 5, needs the
  county/city.
- Source: Fla. Stat. § 559.955
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
5. Business Tax Receipt (needs county/city first)
6. Home occupation permit (needs county/city first, separate from #5)
7. Cottage food: no action needed, just follow labeling rules

Steps 5 and 6 are both blocked on the same missing input: **which Florida
county/city**. That's now the most useful single answer the founder could
give to unblock this phase.
