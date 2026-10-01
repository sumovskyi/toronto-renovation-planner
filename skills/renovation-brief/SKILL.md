---
name: renovation-brief
description: >
  This skill should be used when a homeowner is ready to contact contractors or wants comparable quotes:
  "write a renovation brief", "what should I send contractors", "how do I describe my project",
  "request for quote", "I want apples-to-apples quotes", "prepare for the estimate visit", "what photos
  and measurements do contractors need", "scope of work for my basement / kitchen / bathroom / addition".
  Turns the homeowner's wishes into a clear one-page project brief (scope, must-keep items, budget band,
  timing, photos and measurements checklist) they can send to any contractor.
metadata:
  version: "0.2.0"
---

# Renovation brief: one page that gets better, comparable quotes

Contractors quote what they understand. A clear brief sent to all three means quotes that can be compared line by line
and fewer surprises later. The homeowner sends it to contractors of their choice.

## Steps

1. **Collect only what the brief needs** (ask in one message, skip what's known): project and rooms; goal ("what should it do?"); what must stay; approximate size; the house (age, known issues like water, low ceiling, old wiring); finish level (basic / mid / high-end, or 2–3 example photos they like); budget band; timing and what drives it (closing date, baby, tenant, season); permit status or existing drawings; how they prefer to be contacted.
2. **Write the brief** in this order:
   - **Project summary** (2 sentences, their goal in plain words)
   - **Scope list**: what's included, as checklist lines using the matching list in `contractor-quote-checker/references/quote-checklists.md`
   - **Must keep / must not change**
   - **Allowances**: ask each contractor to show allowances separately (flooring, tile, fixtures, cabinets, countertops)
   - **Known conditions** and questions for the site visit
   - **Budget band and timing**: a band, not a single number ("$55–75K"), and the target start/finish window
   - **What we'd like in every quote**: itemized lines, allowances, exclusions, permits (who applies), schedule, payment schedule (deposit ~10% or less), warranty terms, change-order process, WSIB clearance and insurance certificate
   - **Photos and measurements attached** (see the checklist below)
3. **Photo and measurement checklist** tailored to the project, for example:
   basement: each wall, the ceiling at the lowest beam/duct with a tape measure, the floor drain, electrical panel label, furnace/water heater, windows, any water marks · kitchen: each wall, appliance labels, the panel, the ceiling, the floor · bathroom: fixtures, the ceiling fan, under the vanity, tile edges · addition: the back of the house, the lot, the survey if they have one.
4. **Offer formats**: a copy-paste email version, and a printable page.

## Rules
- Neutral: the brief works with any contractor. Don't insert a contractor's name unless the user asks.
- Don't include personal data the user didn't choose to include; suggest they add their contact details themselves.
- A budget band helps contractors propose the right scope. Explain that sharing it is optional.

## Output
The brief (headings above), then "Send it to 3 contractors and compare with `contractor-quote-checker`."
