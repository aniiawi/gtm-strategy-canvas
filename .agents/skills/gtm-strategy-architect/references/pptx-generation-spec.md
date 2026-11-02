# Editable PowerPoint Generation Specification

## Purpose

The primary GTM Strategy Architect deliverable is a practical, editable strategy board in PowerPoint. It must support ongoing work, not merely present a finished narrative.

## Document setup

- Format: 16:9 widescreen.
- Language: English by default; use the user's requested language for generated strategy content.
- Visual direction: light neutral background, dark readable text, restrained teal accent.
- Typography: one clear sans-serif family with consistent hierarchy.
- Use generous spacing, aligned grids, and concise copy.
- Avoid decorative visuals that reduce editing space.

## Slide architecture: 14 slides

### Slide 1 — GTM Overview

Show all 12 canonical blocks in a 4-column × 3-row grid. Each block card includes:
- Block number and canonical title.
- One-line strategic conclusion.
- Key decision.
- Evidence status.
- Open question or next action.

Do not merge or omit blocks. Use consistent status labels: Validated, Supported, Hypothesis, Unknown.

### Slides 2–13 — Detailed block worksheets

Create one slide per Canvas block, in canonical order. Each slide should include:
- Objective.
- Key questions.
- Relevant frameworks (only those actually used).
- Findings and evidence, with source/date where available.
- Strategic decision and rationale.
- Alternatives and trade-offs.
- Assumptions and risks.
- Dependencies on other blocks.
- Next actions, owner, and success criterion where known.

Use editable sections and tables. Preserve empty fields as prompts or explicit Unknown values; do not invent content to make the slide look complete.

### Slide 14 — Strategy Integrity & Next Steps

Include:
- Overall readiness: Strategic Draft / Strategically Coherent / Evidence-Backed.
- Cross-Canvas consistency assessment.
- Critical and major contradictions.
- Most consequential assumptions.
- Validation experiments.
- Top next actions and owners.
- Decisions requiring approval.

## Editability requirements

All text and visual components must be native PowerPoint objects:
- Text boxes.
- Shapes.
- Lines and connectors.
- Tables built from editable shapes or native tables.

Do not flatten slides into screenshots or background images. Do not place the entire slide as a single image. Keep labels, statuses, cards, and text independently editable and movable.

## Data and content rules

- Never fabricate evidence, metrics, sources, dates, owners, or financial projections.
- Preserve evidence status at claim level where possible.
- Clearly label estimates and assumptions.
- Include concise source references on slides and fuller source details in speaker notes or an appendix if required.
- Keep strategy decisions distinct from open questions and recommendations.
- Fit text to the slide without reducing readability; move detail to notes or supporting material rather than shrinking type excessively.

## Visual system

Suggested palette:
- Background: warm white / very light grey.
- Primary text: charcoal / deep navy.
- Accent: restrained teal.
- Evidence status: neutral, accessible labels with both text and visual distinction.
- Risks: subtle amber/red only when severity warrants it.

Maintain consistent spacing, card geometry, alignment, and typography. Use color sparingly and never rely on color alone to communicate status.

## Quality checks before delivery

1. Exactly 14 slides.
2. Overview contains all 12 blocks in canonical order.
3. Slides 2–13 each map to exactly one block.
4. Slide 14 includes integrity and next steps.
5. All content is editable.
6. No text overflow, clipping, or illegible type.
7. Evidence statuses and readiness labels are consistent.
8. No unsupported claims are presented as facts.
9. Cross-Canvas contradictions are visible.
10. The file opens successfully in PowerPoint and compatible editors.

## Fallback

If binary PowerPoint generation is unavailable, deliver structured slide content and disclose that the editable PPTX has not yet been generated. Never claim a template exists until the actual file is committed and verified.
