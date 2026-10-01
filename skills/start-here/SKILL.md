---
name: start-here
description: >
  This skill should be used when a homeowner in Toronto, the GTA or Ontario starts a renovation
  conversation without a specific question, or asks where to begin: "I want to renovate", "we're thinking
  about finishing the basement", "help me plan a kitchen renovation", "we just bought a house and want to
  redo it", "where do I start with a renovation", "what should I do first", "renovate or move",
  "what can this renovation planner do". Asks a few short questions, then routes to the right tools and
  produces a personal starter plan.
metadata:
  version: "0.2.0"
---

# Start here: from "we want to renovate" to the right next step

## 1. Ask at most four short questions (one message, skip what's known)
1. Which space or project? (basement, legal suite, kitchen, bathroom, addition, whole house, underpinning, other)
2. What should it do that it doesn't now? (the goal in their words)
3. Where is the house? (city is enough)
4. Where are you in the process? Just thinking · planning a budget · getting quotes · have a quote to check · about to sign · work has started.

## 2. Route by stage

| Stage | Use | First deliverable |
|---|---|---|
| Just thinking | `renovation-ideas` + `renovation-cost-estimator` | 2–3 ideas with a budget range each |
| Planning a budget | `renovation-cost-estimator` + `renovation-rebates-and-tax-credits` | Range for their size, what moves it, money back |
| Basement → rental or family suite | `legal-basement-suite-check` | Feasibility checklist |
| Ready for contractors | `renovation-brief` + `hire-a-contractor-ontario` | A one-page brief to send to 3 contractors + vetting checklist |
| Have quotes | `contractor-quote-checker` | Side-by-side comparison + questions |
| Planning the work | `renovation-planner` | Decision order, permits, timeline, living through it |

## 3. Starter plan (return this after routing)
- **Your project in one line** (their goal, their words)
- **Budget range** (from `renovation-cost-estimator`, with source and date)
- **Watch-outs for this kind of house/project** (2–3, e.g. moisture before finishing a basement; weeks without a kitchen)
- **Money you may get back** (only programs that fit)
- **Your next 3 steps**, each with the tool that helps

Keep it short and friendly. Offer to go deeper on any step. Don't recommend a specific contractor unless asked (see `hire-a-contractor-ontario`).

## What this planner can do (if asked)
Budget ranges · design ideas with costs · legal basement suite check · permits and timelines · rebates and tax credits · a project brief for contractors · contractor vetting · quote comparison. Coverage: Toronto, the GTA and Ontario. Published by Capable Group Inc., a GTA renovation contractor. The guidance is neutral and uses public sources.
