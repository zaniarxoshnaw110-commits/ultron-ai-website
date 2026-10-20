---
name: scroll-driven-3d
description: Build responsive, scroll-scrubbed cinematic 3D experiences with native canvas/CSS, accessible motion states, and measured performance.
---
# Scroll-Driven 3D Experience

## Intent
Scrolling is the timeline, not merely a trigger for generic fade-ins. Use depth, perspective, camera rotation, layered parallax, and chapter transitions to make the site's argument feel spatial. Keep the visual metaphor tied to Ultron's question → examine → prove loop.

## Design rules
- Establish the static hierarchy and narrative before adding motion. Every animated layer must reinforce the message or orientation.
- Let scroll progress drive the primary camera/geometry state. Time-based motion is secondary and pauses outside the viewport.
- Prefer a dependency-free projected canvas or CSS 3D for this static site. Add no remote library solely for spectacle.
- Use depth through scale, perspective, occlusion, contrast, and different parallax speeds; avoid random floating UI and excessive HUD decoration.
- Keep readable copy above visuals, keep controls reachable, and preserve a meaningful static fallback.

## Performance and accessibility
- Cap device pixel ratio, use requestAnimationFrame, passive scroll listeners, and IntersectionObserver to avoid offscreen rendering.
- Respect `prefers-reduced-motion`; remove continuous motion and keep the essential narrative available.
- Test narrow screens, low-height screens, resize, tab visibility, keyboard navigation, and missing canvas support.
- Never imply procedural art is a real neural network, model telemetry, or live AI output.

## Verification
- Check JavaScript syntax and all asset paths.
- Check scroll progress at top, middle, bottom, and on reverse scroll.
- Verify chapter labels match the active range and the progress indicator never leaves 0–100%.
- Confirm deployment independently from commit success and disclose if no browser visual inspection was possible.

## Research inspiration
- https://github.com/zubair-trabzada/scroll-cinematic-claude
- https://github.com/Krishna-Modi12/frontend-design-pro
- https://github.com/obra/superpowers
