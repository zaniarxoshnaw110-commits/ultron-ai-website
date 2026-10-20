# Ultron scroll-cinematic experience

## Interaction thesis
The site now uses scroll as a continuous narrative timeline: question → examine → prove. A pinned viewport holds a procedural projected 3D structure while the camera rotation, geometry twist, and chapter progress respond to scroll. Supporting orbit layers use CSS perspective; the hero artwork tilts subtly based on scroll position.

## Implementation
- Plain HTML/CSS/JavaScript and a projected canvas; no runtime dependency added.
- A 0–100% progress meter and three chapter states update from the section's scroll range.
- Canvas pixel ratio is capped; drawing pauses outside the viewport or when the tab is hidden.
- `prefers-reduced-motion` removes continuous canvas animation and keeps a static narrative state.
- The visual is explicitly described as procedural art, not model telemetry. The local lab remains a preset prototype, not live AI.

## Quality gates
The Pages workflow checks required markup, reduced-motion styling, the local prototype disclaimer, and JavaScript syntax before deployment. Commit, deployment, and browser visual inspection are separate evidence; the latter should not be claimed unless actually performed.

## Research references
- https://github.com/zubair-trabzada/scroll-cinematic-claude
- https://github.com/Krishna-Modi12/frontend-design-pro
- https://github.com/educlopez/ui-craft
- https://github.com/google-labs-code/stitch-skills
- https://github.com/obra/superpowers
