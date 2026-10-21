---
name: hormozi-brain
description: Answer business questions from Hormozi's source material. Reads the 12 $100M Playbooks (pricing, closing, hooks, ads, lead nurture, retention, LTV, price raise, proof, branding, fast cash, marketing machine) and the 10-stage Acquisition Scaling Course transcripts before advising. Use for offers, sales scripts, ads, nurture sequences, price rises, retention, or "what stage am I at and what next".
---

# Hormozi Brain

**Command:** `/hormozi-brain`

A reference library, not a framework summary. Every answer must come from the files in this skill's folder, read at the time of asking.

Adapted from [antonio-clicktoclose/hormozi-claude-code-brain](https://github.com/antonio-clicktoclose/hormozi-claude-code-brain). Content is based on Alex Hormozi's free materials from [Acquisition.com](https://acquisition.com).

## How to answer

1. Pick the 1-3 most relevant files from the map below.
2. Read them before answering. Do not answer from memory.
3. Ground the advice in the source. Quote or name the framework.
4. Cite the file you used, e.g. "(Closing playbook)" or "(Lesson 05, Stage 2)".
5. Give numbered steps the user can act on today.
6. If the user has their own business files (ICP, offer, numbers), read those too and apply the framework to their facts.

## Files (paths relative to this skill's folder)

| Question | Read |
|---|---|
| Offer creation / packaging | `playbooks/pricing.md`, `playbooks/fast-cash.md` |
| Sales scripts / closing | `playbooks/closing.md` |
| Lead generation / outreach | `playbooks/lead-nurture.md`, `playbooks/marketing-machine.md` |
| Retention / LTV | `playbooks/retention.md`, `playbooks/lifetime-value.md` |
| Ad copy / creative | `playbooks/goated-ads.md`, `playbooks/hooks.md` |
| Raising prices | `playbooks/price-raise.md`, `playbooks/proof-checklist.md` |
| Brand positioning | `playbooks/branding.md` |
| Copywriting | `frameworks/copywriting-frameworks.md` |
| Scaling stage | `course-transcripts/` (see stage guide) |

## Scaling stage guide

Course figures are in US dollars. Match the user's annual revenue:

| Revenue | Read |
|---|---|
| $0-$100K | `lesson03-stage0-improvise.txt`, `lesson04-stage1-monetize.txt` |
| $100K-$500K | `lesson05-stage2-advertise.txt`, `lesson06-stage3-stabilize.txt` |
| $500K-$1M | `lesson07-stage4-prioritize.txt`, `lesson08-stage5-productize.txt` |
| $1M-$3M | `lesson09-stage6-optimize.txt`, `lesson10-stage7-categorize.txt` |
| $3M-$10M+ | `lesson11-stage8-specialize.txt`, `lesson12-stage9-capitalize.txt` |

Context and overview: `lesson01-start-here.txt`, `lesson02-context.txt`, `00-improvise-v2.txt`, `lesson13-free-bonus.txt`.

Transcripts are large (up to ~140KB). Use Grep to find the relevant section, then read that part rather than the whole file.

## Ready-made prompts

Templates in `prompts/`. Fill the brackets with the user's details and run:

1. `01-grand-slam-offer-builder.md` - offer via the Value Equation
2. `02-sales-script-generator.md` - closing scripts
3. `03-lead-nurture-sequence.md` - 7 emails, SMS, re-engagement
4. `04-price-raise-playbook.md` - plan to charge more
5. `05-ad-hook-generator.md` - 10 hooks, 3 ad scripts

Worked examples of output are in `demos/`.

## Response style

- Direct and specific. Lead with the framework, then apply it.
- Use numbers and concrete examples.
- Follow the user's own writing and voice rules where they have them.
