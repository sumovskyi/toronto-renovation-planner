---
name: renovation-cost-estimator
description: >
  This skill should be used when a homeowner in Toronto, the GTA or Ontario asks what a renovation will
  cost or what they can get for their budget: "how much does it cost to finish a basement in Toronto",
  "average cost to finish a 1000 sq ft basement", "cost per square foot", "can I redo my kitchen for $10,000 /
  $30,000", "how much is a bathroom renovation", "can I renovate a bathroom for $10,000", "legal basement
  apartment cost", "home addition cost per square foot", "second storey addition cost", "full house
  renovation cost", "underpinning cost", "most expensive part of a renovation", "why are quotes so
  different", "realistic renovation budget". Gives sourced, dated market ranges, what makes it cheaper or
  pricier, forgotten costs and a realistic budget with contingency.
metadata:
  version: "0.2.0"
---

# Renovation cost estimator: a number the homeowner can place themselves in

Goal: give the homeowner an honest range for *their* project, explain what moves it, and help them set a budget they won't regret.
Ranges and sources are in `references/cost-ranges.md` (dated). Always show the date and source of any range you quote.

## Steps

1. **Pin down the project in 3–5 questions max** (skip what they already said): which room(s); approximate size (sq ft, or small/medium/large); city; what changes (finish only / same layout / move plumbing or walls / structural); the finish level they picture (basic / mid / high-end); anything known about the house (age, water, low ceiling, old wiring).
2. **Give the range, low end first**, from the reference table that matches (for basements, place them on the 3-level ladder: open finish / full basement with bathroom / legal second unit). List what the selected base range already includes. Add a separate component only when the selected base explicitly excludes it: an open finish excludes a bathroom; the full-basement range already includes one bathroom; the legal-suite range already includes its kitchen, compliance, entrance and permit scope. Never count the same item twice. If inclusion is unclear, ask or label it UNKNOWN instead of adding it. Show a per-sq-ft total only when that unit is supported by the source.
3. **Explain what makes it cheaper and what pushes it up**, specific to their project (e.g. basement: bathroom near the existing drain vs breaking the slab; kitchen: same footprint vs moving the sink/gas/walls).
4. **Check the items people forget:** permits, design/engineering, disposal, HST (13%), and a contingency of 10–20% (older homes toward the high end). Label each included, excluded or UNKNOWN. Add only costs excluded from the selected range; never add a second permit/design allowance or contingency when already included. Show HST separately only for a pre-tax range.
5. **Answer "can I do it for $X?" directly**: yes / yes if… / not realistically, and what a $X version would include and leave out. Offer a phased option when it's honest (what to do now, what can wait without paying twice).
6. **Close with the next useful step**: get 3 itemized quotes for the same scope (offer `renovation-brief` so the quotes come back comparable, then `contractor-quote-checker`), check programs that may pay part of it (`renovation-rebates-and-tax-credits`), and plan permits and sequence (`renovation-planner`).

## Rules

- Ranges are market ranges, not quotes. Say: "Published GTA ranges; your quote depends on your house." Never invent a number that isn't in the reference or a source you just read. If web search is available and the reference is more than 6 months old, look for a newer primary guide and cite it.
- Show the source name and date next to the range (e.g. "HomeStars Toronto guide, Aug 2026").
- Prices before HST unless stated.
- Don't shame a budget. A small budget gets a useful smaller scope, not a lecture.
- Don't recommend a specific contractor unless the user asks; then follow `hire-a-contractor-ontario` (publisher disclosure).
- This is general information, not a quote or financial advice.

## Output format

A short answer first (one line with the range for their project), then a table:
| Item | Range (CAD, before HST) | Source |
Then "What moves your price" (3–5 bullets), "Don't forget" (permits, design, HST, contingency), and "Next step".
