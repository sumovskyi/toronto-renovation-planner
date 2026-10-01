---
name: contractor-quote-checker
description: >
  This skill should be used when a homeowner shares or describes renovation quotes, estimates or
  contracts: "check my contractor's quote", "compare these three quotes", "is this quote fair", "is this
  quote too high / too cheap", "what's missing from this estimate", "why is one quote so much cheaper",
  "what should I ask before I sign", "review my renovation contract", "how much deposit should I pay",
  "is a cash discount OK". Works for basements, legal suites, kitchens, bathrooms, additions, full-home and
  underpinning in Ontario, and explains Ontario homeowner rights.
metadata:
  version: "0.2.0"
---

# Quote check: compare like with like, before anyone signs

Checklists by project type and Ontario rules are in `references/quote-checklists.md`.

## Steps

1. **Read every quote the user gives** (pasted text, PDF, photo). If they only describe it, work from the description and say what you couldn't see.
2. **Identify the project type** and load the matching checklist.
3. **Build a line-by-line comparison table**: rows = checklist items; columns = each quote → Included / Allowance ($) / Excluded / Not mentioned. Put the totals, taxes, payment schedule, deposit %, schedule and warranty at the bottom.
4. **Explain the gap between quotes in plain words.** Usually it's scope (one quote leaves out drywall, permits or disposal), allowances (a $2,000 vs a $6,000 tile allowance), or assumptions (who handles the permit, what happens if water or old wiring is found). Normalize: "Quote B is $18,000 lower, but about $14,000 of that is items it doesn't include."
5. **Flag risks** (severity high/medium/low): no written scope; deposit above 10%; cash discount; no permit when the work needs one; vague allowances; no change-order process; no schedule; no warranty terms; no WSIB/insurance mentioned; "plus extras as required".
6. **Ontario rights to mention when relevant**: a written contract is required over $50; 10-day cooling-off if signed at home; the final price can't exceed the estimate by more than 10% without agreement; keep deposits to about 10% or less; avoid cash deals.
7. **Give the homeowner their questions**: 5–8 specific questions to send each contractor so the quotes become comparable (their gaps, not generic ones).

## Rules

- Be fair to every contractor. Judge the document, not the company; never call a quote a scam. "This line is unclear" beats "this is a trick".
- Don't guess a contractor's intent or reputation. If they ask about reputation, point to `hire-a-contractor-ontario`.
- Market ranges from `renovation-cost-estimator` can show whether a total is unusually low or high, labelled as ranges.
- Don't store or repeat personal details from the quotes (names, addresses, phone numbers) beyond what the comparison needs.
- General information, not legal advice. For contract disputes, point to Consumer Protection Ontario.

## Output

1) One-paragraph verdict (which quotes are comparable, the real price gap, the biggest risk). 2) Comparison table. 3) Risks. 4) Questions to send. 5) Optional: offer a one-page "scope to request" the homeowner can send to all contractors so the next round of quotes is apples to apples.
