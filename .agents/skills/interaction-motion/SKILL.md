---
name: interaction-motion
description: Design motion that communicates state and spatial relationships without distracting from content or blocking input.
---
# Interaction and Motion

- Motion must communicate a state change, focus, depth, or transition; remove decoration that adds no information.
- Keep easing smooth and durations short for controls; use slower motion only for atmospheric artwork.
- Use requestAnimationFrame for canvas animation and passive scroll listeners with frame throttling.
- Never hijack scroll, autoplay sound, flash, or hide essential content behind animation.
- Respect prefers-reduced-motion: stop continuous canvas motion and disable reveal transitions.
- Pause animated work when the document is hidden; resume only when visible.
- Pointer motion is optional enhancement; the site must remain understandable and fully usable on touch screens.
- Test focus, hover, active, selected, reset, and empty-input states.