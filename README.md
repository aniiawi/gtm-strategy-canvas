# GTM Strategy Architect

An evidence-led agent skill for developing, reviewing, and improving go-to-market strategies. It uses a 12-block GTM Canvas as a strategic workspace, not as a form to fill in.

The agent helps product marketers, product leaders, and founders make connected GTM decisions, assess evidence, expose assumptions, and turn strategy into an editable PowerPoint working board.

## What it does

- Diagnoses the user's starting point before choosing a workflow.
- Adapts to new-product, new-market, GTM-review, and specific-problem scenarios.
- Uses relevant market, customer, product, positioning, monetization, growth, and execution frameworks.
- Distinguishes facts from interpretations, hypotheses, and unknowns.
- Records decisions, alternatives, rationale, evidence, confidence, and trade-offs.
- Checks dependencies and contradictions across all 12 Canvas blocks.
- Produces a 14-slide editable PowerPoint board as the primary deliverable.

## The 12-block GTM Canvas

1. Market Intelligence
2. Customer & Segmentation
3. Market Entry Strategy
4. Product Readiness
5. Positioning & Differentiation
6. Business & Monetization Model
7. GTM Motion & Distribution
8. Launch & Enablement
9. Execution & Economics
10. Validation & Optimization
11. Risks & Considerations
12. Key Metrics

The block names and order are canonical. See [Canvas Methodology](methodology/canvas-methodology.md).

## Repository structure

```text
.
├── SKILL.md
├── README.md
├── LICENSE
├── manifest.json
├── methodology/
│   ├── canvas-methodology.md
│   ├── decision-logic.md
│   ├── decision-record.md
│   ├── research-protocol.md
│   └── quality-assurance.md
├── templates/
│   └── README.md
├── output/
│   └── pptx-generation-spec.md
└── evaluation/
    ├── test-cases.md
    ├── decision-logic-tests.md
    └── output-quality-tests.md
```

## Quick start

Install or expose this skill in an agent environment that supports the Agent Skills format. Start with:

> Help me develop a GTM strategy for [product] in [market]. First diagnose what we already know, then guide me through the decisions that matter.

You can also request a focused workflow:

- Review an existing GTM strategy.
- Prioritize a beachhead segment.
- Evaluate pricing and packaging options.
- Diagnose a conversion or activation problem.
- Stress-test GTM assumptions and economics.

## Operating principles

1. Strategy before documentation: do not fill every block mechanically.
2. Evidence before confidence: never invent market, customer, product, or financial data.
3. Adaptive sequencing: work on the decisions that matter now, respecting dependencies.
4. Explicit trade-offs: recommendations must explain what is gained and what is sacrificed.
5. Cross-functional coherence: choices in one block must be checked against the others.
6. Honest readiness: a polished Canvas is not automatically a validated strategy.

## Evidence statuses

- **Validated** — directly supported by reliable evidence relevant to the decision.
- **Supported** — credible evidence exists, but coverage or strength is incomplete.
- **Hypothesis** — plausible and testable, but not yet sufficiently evidenced.
- **Unknown** — information is missing or cannot currently be assessed.

## Primary output

The main deliverable is a 16:9, 14-slide PowerPoint:

- Slide 1: GTM Overview with all 12 blocks.
- Slides 2–13: one detailed working slide per Canvas block.
- Slide 14: Strategy Integrity & Next Steps.

All content should use native PowerPoint text boxes and shapes so users can edit and move individual elements. See [PPTX Generation Specification](output/pptx-generation-spec.md).

## Methodology and evaluation

- [Decision Logic](methodology/decision-logic.md)
- [Decision Record](methodology/decision-record.md)
- [Research Protocol](methodology/research-protocol.md)
- [Quality Assurance](methodology/quality-assurance.md)
- [Decision Logic Tests](evaluation/decision-logic-tests.md)
- [Output Quality Tests](evaluation/output-quality-tests.md)

## Status

This project is under active development. The methodology and output specification define intended behavior; they do not imply that every feature is already implemented or automatically validated.

## License

See [LICENSE](LICENSE).
