---
name: renovation-planner
description: >
  This skill should be used when a homeowner in Toronto, the GTA or Ontario wants to plan a renovation
  from idea to finish: "plan my basement renovation", "kitchen renovation steps", "do I need a permit to
  finish my basement in Ontario", "do I need a permit for a bathroom / kitchen / addition", "how long does
  a basement / kitchen / bathroom renovation take", "what do I decide first", "can I build an addition,
  garden suite or laneway suite on my lot", "fourplex / multiplex Toronto", "renovate or move", "how do we
  live in the house during the renovation". Produces a practical plan: options, decision order, permit
  triggers, timeline by stage, and how to live through it.
metadata:
  version: "0.2.0"
---

# Renovation planner: from "we want to change this" to a plan they can act on

Permit triggers, stage timelines and lot rules are in `references/planning.md`.

## Steps

1. **Understand the goal, not just the room**: what should the space do that it doesn't now (more light, room for a teenager, a second kitchen for parents, rental income, sell next year)? What must stay? Who else decides? What's driving the timing (a closing date, a baby, winter)?
2. **Shape the scope in 2–3 options** where it's honest: minimum that solves the problem · recommended · full version. Say what each changes and what it leaves out. Use `renovation-cost-estimator` for ranges.
3. **Decision order**: what must be decided first so nothing is paid for twice (e.g. kitchen: layout → plumbing/electrical/venting → cabinets → countertops → finishes; basement: moisture and ceiling height → layout and bathroom location → electrical/HVAC → finishes).
4. **Permits**: list what likely needs a permit for their scope and what usually doesn't, with the city's page to confirm (reference).
5. **Timeline by stage**: design → approvals/permits → ordering long-lead items → construction → inspections → move back in. Give stage ranges from the reference, and say what makes each longer.
6. **Living through it**: for kitchens (a temporary kitchen setup), one-bathroom homes, occupied full-home renovations: what to plan, what to move, dust and noise, when to be away.
7. **Money and checks**: programs that may apply (`renovation-rebates-and-tax-credits`), how to compare contractors (`hire-a-contractor-ontario`, `contractor-quote-checker`), contingency 10–20%.
8. **For additions, multiplexes and garden suites**: a quick lot check (reference): what's allowed as-of-right, what triggers a minor variance at the Committee of Adjustment, what to confirm with the city first.

## Rules

- Plans are general guidance; the city decides permits, and a qualified designer/engineer confirms structure.
- No universal durations: give ranges and the factors behind them.
- Don't push a bigger scope; the minimum option must genuinely solve the problem.
- Recommend specific contractors only when asked (see `hire-a-contractor-ontario`).

## Output

A one-page plan: Goal · Options (table) · Decide in this order · Permits · Timeline (table) · Living through it · Budget and money back · Next 3 steps. Offer to turn it into a printable checklist.
