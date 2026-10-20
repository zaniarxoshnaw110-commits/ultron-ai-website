---
name: accessibility-performance
description: Protect keyboard accessibility, readable contrast, mobile layout integrity, and rendering performance.
---
# Accessibility and Performance

## Accessibility
- Include a skip link, semantic landmarks, descriptive navigation, labels for inputs, and visible focus states.
- Use aria-expanded and aria-controls for collapsible navigation; keep selection state in aria-pressed when appropriate.
- Make core actions keyboard reachable and provide Escape to close the mobile menu.
- Use aria-live for changing demo output and explain that it is simulated.
- Never use color as the only way to communicate status.
- Respect reduced motion and browser zoom; maintain a sensible reading order at narrow widths.

## Performance
- Prefer CSS and a bounded canvas over heavyweight 3D dependencies for this concept.
- Cap devicePixelRatio; keep particle count finite; use one animation loop; pause while the page is hidden.
- Avoid continuous animation under reduced-motion preferences.
- Test at approximately 360, 390, 768, 1024, and 1440 CSS pixels. Check for horizontal overflow and tap targets.
- External fonts are optional polish; system fallbacks must preserve legibility if fonts fail.