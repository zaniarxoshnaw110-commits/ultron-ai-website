---
name: superpower-workflow
description: A disciplined implementation workflow for ambitious changes: clarify intent, plan in small steps, use focused review passes, validate behavior, and report evidence honestly.
---
# Superpower-Style Build Workflow

> Project-local workflow skill. It is not represented as an official or pre-existing Composio skill.

## Before implementation
1. Restate the user outcome and define what “better” means in observable terms.
2. Inspect current files, existing behaviors, deployment configuration, and local project instructions.
3. Make a compact plan spanning visual design, content, interaction, accessibility, performance, and verification.
4. Identify assumptions and capability claims that must remain honest.

## Implementation passes
1. Structure pass: build the semantic page outline and user journey.
2. Art-direction pass: define tokens, typography, contrast, grid, and original visual signature.
3. Interaction pass: wire every advertised control, empty state, keyboard path, reset path, and mobile navigation.
4. Accessibility pass: review headings, labels, focus, reduced motion, live updates, contrast, and touch layouts.
5. Performance pass: bound animation work, avoid needless dependencies, and provide static fallbacks.
6. Truth pass: remove unsupported product claims and mark simulations clearly.
7. Review pass: inspect diffs, search for dead links/selectors, verify content and scripts, and check for accidental secrets.

## Verification discipline
- Do not infer that a site is live from a successful commit.
- Re-read the committed source and check CI/deployment status.
- If browser rendering tools are available, inspect desktop and mobile widths and check the console; otherwise state that visual browser verification remains outstanding.
- Report what changed, what passed, what failed, and what remains unverified. Never fabricate test results.

## Definition of done
A cohesive user experience is implemented; controls work as advertised; mobile and reduced-motion paths are considered; product claims are honest; source is committed; deployment and live render are checked separately; limitations are stated plainly.