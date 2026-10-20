---
name: accessibility-performance
description: Review accessibility, responsive behavior, motion preferences, and rendering performance for static interactive sites.
---
# Accessibility and Performance
- Use semantic landmarks, a logical heading structure, skip navigation, accessible labels, and visible keyboard focus.
- Keep contrast and tap targets usable on small screens; avoid horizontal overflow.
- Honor prefers-reduced-motion and provide a useful non-animated fallback.
- Bound canvas pixel ratio and particle count; pause animation when the document is hidden.
- Avoid unnecessary dependencies, layout thrashing, and repeated work inside animation frames.
- Test keyboard-only navigation and all interactive states, not just the default view.