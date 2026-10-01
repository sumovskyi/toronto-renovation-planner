---
name: legal-basement-suite-check
description: >
  This skill should be used when a homeowner in Ontario asks whether a basement or other space can
  become a legal second unit, basement apartment, secondary suite, in-law suite or rental unit: "can my
  basement be legal", "legal basement requirements Ontario", "legal vs illegal basement apartment", "how to
  legalize a basement in Brampton / Mississauga / Toronto / Vaughan / Markham", "minimum ceiling height for a
  basement apartment", "egress window size Ontario", "fire separation", "separate entrance", "is
  underpinning worth it for a suite", "basement apartment permit". Runs a self-check against Ontario
  Building Code minimums, points to the right city page, and outlines fixes, costs and next steps.
metadata:
  version: "0.2.0"
---

# Legal suite self-check: find the deal-breakers before paying for drawings

Rules, minimums and city links are in `references/suite-rules.md`. This is a screening tool, not an approval:
final requirements depend on the property and the city's review.

## Steps

1. **Ask only what the check needs**: city; house type (detached / semi / town); building age; existing and proposed unit count; whether the unit is inside the existing house or an accessory building; ceiling height at its lowest (under beams/ducts) and in open areas; window sizes and sill heights in rooms that would be bedrooms; existing side/rear entrance or walkout; is the suite for rent or family; any known water issues; electrical panel size if known.
2. **Establish the applicable code/exit pathway first**, using the reference. Missing age, unit count or exit context means CHECK. Run a measurement checklist (pass / check / likely fail for the applicable item only, with the reason):
   - Ceiling measurements against the applicable existing-house pathway (guide figures 1.95 m generally / 1.85 m under beams and ducts); these figures do not approve the whole suite
   - Applicable egress/escape pathway: distinguish 0.35 m² / 380 mm bedroom egress from the separate 0.38 m² / 460 mm escape-window pathway. Do not impose a universal 900 mm sill limit; check direct exterior-door exceptions, fixed steps and window-well clearance
   - Exit/entrance
   - Applicable smoke-tight-barrier or rated-separation design, plus smoke and CO alarm requirements (CHECK with qualified designer/city)
   - Heating/ventilation separation
   - Electrical service capacity
   - City-specific: zoning/parking, registration (e.g. Brampton, Mississauga), permit path
3. **For each "likely fail", give the fix and its cost range** (e.g. low ceiling → underpinning or benching; small window → enlarge the window opening, often with a window well), using `renovation-cost-estimator` ranges.
4. **Money that may apply**: the federal Multigenerational Home Renovation Tax Credit (if the suite is for a senior or an adult with a disability living with a relative), and Toronto's flooding-protection subsidy for a backwater valve or sump pump. Details: `renovation-rebates-and-tax-credits`.
5. **Next steps**: confirm with the city's zoning/permit office, get drawings from a qualified designer (BCIN) or architect, and get 3 itemized quotes that include fire separation, egress and permits (`contractor-quote-checker`).

## Rules

- Never promise approval, rent or return on investment. Rent and payback depend on the market and the property.
- Cite the official source for every rule; link the city page rather than paraphrasing rules you haven't read on it.
- Code numbers come from a specific existing-house second-unit guide. Applicability depends on age, unit count and exit design; accessory-building units and third units are outside that guide. Cities also control zoning, parking and registration. Never present the guide as a universal legal-suite standard.
- General information, not legal or engineering advice.

## Output

Screening summary in one line (what the measurements suggest and what remains CHECK; no whole-suite approval verdict) → checklist table → fixes and cost ranges → money that may apply → next steps with official links.
