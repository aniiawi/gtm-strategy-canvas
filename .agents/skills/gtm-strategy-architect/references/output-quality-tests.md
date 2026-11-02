# Output Quality Evaluation Suite

## Purpose

Verify that the agent produces a usable strategic Canvas and an editable PowerPoint, not merely plausible-looking prose.

## A. Canvas structure

- [ ] Exactly 12 blocks are present.
- [ ] Canonical block names, order, and separation are preserved.
- [ ] Each block has a strategic conclusion or an explicit Unknown / Not Applicable.
- [ ] Decisions are distinguishable from hypotheses, recommendations, and open questions.
- [ ] No block is silently omitted because evidence is missing.

## B. Evidence and decision quality

- [ ] Material claims have evidence statuses.
- [ ] Sources include dates and limitations where available.
- [ ] Estimates show method and assumptions.
- [ ] Decisions include rationale, alternatives, trade-offs, confidence, and next action.
- [ ] No invented market data, customer quotes, metrics, or sources appear.
- [ ] Unvalidated assumptions are connected to validation actions.

## C. Cross-Canvas integrity

- [ ] ICP fits market opportunity.
- [ ] Beachhead is supported by customer need and ability to win.
- [ ] Product supports selected use case.
- [ ] Positioning is relevant, differentiated, and provable.
- [ ] Monetization fits customer value and buying behavior.
- [ ] GTM motion fits buying complexity and economics.
- [ ] Launch readiness matches product and operational capability.
- [ ] Resources support the selected motion.
- [ ] Unit economics are internally consistent or explicitly unknown.
- [ ] Risks have mitigations or triggers.
- [ ] Metrics map to intended outcomes.
- [ ] Critical contradictions are visible and resolved or disclosed.

## D. PowerPoint structure

- [ ] Exactly 14 slides.
- [ ] Slide 1 is a 4 × 3 overview of all 12 blocks.
- [ ] Slides 2–13 each cover one block in canonical order.
- [ ] Slide 14 covers strategy integrity and next steps.
- [ ] Every overview card includes conclusion, decision, evidence status, and open question / next action.

## E. PowerPoint editability and usability

- [ ] Text, cards, shapes, tables, and connectors are native editable objects.
- [ ] No slide is flattened into a screenshot.
- [ ] Objects can be selected, moved, and edited independently.
- [ ] No clipping, overflow, overlap, or unreadable text.
- [ ] Layout and typography are consistent.
- [ ] Evidence status is conveyed by text as well as visual styling.
- [ ] Empty or unknown information is clearly marked, not filled with invented content.
- [ ] File opens in PowerPoint and at least one compatible editor.

## F. Final integrity

- [ ] Readiness level is explicitly justified.
- [ ] Most important unknowns are listed.
- [ ] Decisions requiring user approval are identified.
- [ ] Next actions have success criteria and owners where known.
- [ ] Output does not imply research or validation that did not occur.

## Scoring

Score each section A–F:
- 0 = fails or absent.
- 1 = partially meets requirements.
- 2 = meets requirements.

Maximum: 12 points.

Release target: at least 10/12, with no zero in sections A, B, C, D, or E. Any fabricated evidence, flattened-only deck, missing Canvas block, or undisclosed Critical contradiction is an automatic failure.

## Test report

Record:
- Agent version / commit.
- Input scenario and source materials.
- Canvas score and notes.
- PowerPoint score and notes.
- Critical failures.
- Corrective action.
- Regression tests to rerun.
