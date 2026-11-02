# Decision Logic Evaluation Suite

## Purpose

Evaluate whether the agent behaves as an adaptive strategic partner rather than a generic questionnaire or Canvas filler.

These are qualitative scenario tests. They should be run as multi-turn conversations and scored using the rubric below.

## Core scenarios

### 1. New product with limited evidence
**Input:** A founder has an early product concept, a broad market claim, and no paying customers.
**Expected:** Diagnose stage; separate assumptions from facts; narrow customer/problem; avoid fabricated TAM and PMF claims; identify the riskiest assumption and a low-cost test.
**Failure:** Produces a confident full strategy with invented evidence.

### 2. Existing product with a conversion problem
**Input:** User reports low demo-to-close conversion but provides no funnel detail.
**Expected:** Bound the funnel stage; ask for the most diagnostic missing evidence; distinguish lead quality, positioning, product proof, sales process, and pricing.
**Failure:** Immediately recommends more paid traffic or a generic website redesign.

### 3. Conflicting customer evidence
**Input:** Interviews suggest strong demand, but usage and renewal data are weak.
**Expected:** Preserve the conflict; assess sample and behavioral evidence; propose segmentation or follow-up analysis; do not average signals into false certainty.
**Failure:** Cherry-picks interviews or metrics to support a preferred story.

### 4. Product capability contradicts positioning
**Input:** Positioning promises automated outcomes that require manual customer work.
**Expected:** Flag at least a Major contradiction; recommend narrowing the claim, improving capability, or changing target/use case.
**Failure:** Continues writing messaging as if the capability exists.

### 5. Pricing without willingness-to-pay evidence
**Input:** User requests a price recommendation with no WTP, cost, or competitor context.
**Expected:** Clarify pricing objective and value metric; propose a pricing hypothesis and validation method; label any number as illustrative if used.
**Failure:** Presents a precise price as validated.

### 6. Channel recommendation with missing economics
**Input:** User asks whether to prioritize paid search, outbound, or partners but provides no CAC or conversion data.
**Expected:** Compare fit, learning speed, reach, and cost; identify minimum data or test; avoid universal channel claims.
**Failure:** Declares one channel best without context.

### 7. Full strategy request with existing documents
**Input:** User uploads strategy, research, and product docs.
**Expected:** Inspect provided materials, reuse evidence, identify gaps, and ask only consequential questions.
**Failure:** Ignores documents and repeats a generic intake questionnaire.

### 8. Market expansion with unvalidated assumptions
**Input:** User wants to enter a new geography based on competitor presence alone.
**Expected:** Test customer demand, localization, regulation, channel access, and economics; compare entry options.
**Failure:** Treats competitor presence as proof of demand.

### 9. User wants to skip research and move fast
**Input:** User asks for a recommendation today despite uncertainty.
**Expected:** Offer a provisional decision with assumptions, downside, confidence, and a short validation step.
**Failure:** Refuses to help or pretends uncertainty does not exist.

### 10. Contradictory growth targets and unit economics
**Input:** Revenue target requires acquisition volume that exceeds budget or sales capacity.
**Expected:** Reconcile funnel math; flag contradiction; show scenarios and identify which assumption must change.
**Failure:** Repeats targets without checking arithmetic.

## Edge cases

### 11. User has already made a strategic decision
**Expected:** Respect the decision as a constraint, clarify whether it is fixed or open to challenge, and explore implications. Do not silently reopen it.

### 12. Recommendation requested with insufficient information
**Expected:** State what can be concluded, what remains unknown, and give a conditional recommendation or the single most useful question.

## Scoring rubric

Score each dimension 0–2:
1. Context diagnosis.
2. Prioritization of consequential decisions.
3. Adaptive questioning.
4. Evidence discipline.
5. Dependency awareness.
6. Trade-off quality.
7. Contradiction detection.
8. Actionability.

**Maximum:** 16 points.

- 0 = absent or materially incorrect.
- 1 = partially correct, generic, or incomplete.
- 2 = strong, context-aware, explicit, and actionable.

## Critical failure override

Regardless of score, fail the scenario if the agent:
- Fabricates data, sources, customer quotes, or research.
- Presents unsupported claims as Validated.
- Misrepresents product capability.
- Ignores a Critical contradiction.
- Claims Evidence-Backed readiness without adequate support.

## Release acceptance

- Core scenarios: average at least 11/16.
- Critical scenarios involving evidence or contradiction: at least 14/16.
- No critical failure override.
- Re-run affected scenarios after changes to decision logic, evidence handling, research behavior, or Canvas methodology.

## Test execution record

Record prompt, conversation transcript, score by dimension, failure notes, and follow-up fix. Re-run as a multi-turn interaction; a single-turn answer may conceal poor adaptation.
