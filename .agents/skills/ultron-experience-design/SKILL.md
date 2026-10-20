---
name: ultron-experience-design
description: Design the Ultron AI website with Apple-level clarity, original cinematic art direction, procedural 3D-inspired visuals, purposeful motion, and accessible interactions.
---

# Ultron Experience Design Skill

## North star
Ultron values truth over flattery, independent judgment over blind obedience, and concrete progress over impressive-sounding output. The site should feel intelligent, exact, cinematic, and distinct—not a generic SaaS template or a sci-fi game HUD. Each visual must establish character, explain a principle, show a capability, or invite exploration.

## Research method
1. Inspect repository structure, current styles, scripts, assets, and behavior before edits.
2. Use Apple's public Human Interface Guidelines as a quality reference for clarity, deference to content, consistency, feedback, accessibility, and restraint. Never copy Apple's logo, product artwork, or exact page composition.
3. Study real production screens for focal point, type scale, palette, density, section rhythm, and CTA hierarchy.
4. Inspiration research for this concept found a typographic depth tunnel at Leonardo, a luminous object against black at Modal, cinematic light and sparse type at Runway, and restrained dark indigo at xAI. Borrow principles, not layouts or assets.
5. Translate those principles into Ultron's own ember-core particle sculpture and distinct palette.

## Visual tokens
- Background #08090b; surfaces #101114 and #151619.
- Primary text #f3f0e9; secondary text #8c8c91; separators rgba(242,239,231,.13).
- Ember #ff4b35 is the action/emphasis color; amber #ffb45b adds depth; cool highlight #b7c8ff is rare.
- Red is a signal, not wallpaper. Reserve amber for highlights. Keep the majority of the page neutral.
- Space Grotesk for expressive display/interface text; DM Mono for metadata.
- Build hierarchy with scale, line-height, width, weight, and negative space before adding cards. One primary CTA, one quiet secondary action.

## Signature artwork
The core is a procedural 3D-inspired particle sphere drawn on a 2D canvas, depth-sorted with perspective, layered orbital ellipses, glow, and pointer-driven rotation. Keep it dependency-free. Do not describe it as a real neural network or true 3D engine.

## Motion principles
- Slow rotation and damped pointer response; avoid twitchy motion.
- Orbit layers move slowly in counterpoint; no flashing or uncontrolled particles.
- Scroll reveals use a small offset and opacity transition. Content must remain available if JavaScript fails.
- Feedback states should be short, consistent, and visibly distinguishable.
- Use requestAnimationFrame, ResizeObserver when available, bounded particle count, and capped devicePixelRatio.
- Respect prefers-reduced-motion: stop continuous animation and reveal content immediately.
- Never hijack scrolling, autoplay sound, or make information depend on movement.

## Accessibility and responsive behavior
- Semantic landmarks, one H1, descriptive links, named controls, visible focus states, and keyboard operation.
- Target WCAG AA contrast: 4.5:1 normal text, 3:1 large text and essential graphics.
- Test 360, 390, 768, 1024, and 1440px widths; prevent horizontal overflow.
- Support zoom, touch, pointer, reduced motion, and graceful operation if canvas/IntersectionObserver is unavailable.
- Never use color as the only status indicator.

## Workflow and quality gate
1. Read existing page, styles, scripts, and instructions.
2. Define promise and visual signature; adjust tokens before components.
3. Build background, navigation, hero, art, type hierarchy, section rhythm, and CTA before micro-interactions.
4. Add motion only after the static layout reads clearly.
5. Check assets, anchors, keyboard, reduced motion, mobile breakpoints, and console errors.
6. Verify the deployment separately from the commit. A commit does not prove the live page updated.
7. Report exactly what was tested and what remains unverified.

Checklist: distinctive visual signature; consistent tokens; desktop/mobile hierarchy; bounded animation; reduced-motion support; keyboard and touch behavior; honest demo scope; no invented testimonials/metrics; no broken links; successful Pages workflow and separate live-site check.

## Reference sources
- Apple HIG: https://developer.apple.com/design/human-interface-guidelines/
- Apple design principles: https://developer.apple.com/design/human-interface-guidelines/design-principles/
- Leonardo AI: https://leonardo.ai/
- Modal: https://modal.com/
- Runway: https://runwayml.com/
- xAI: https://x.ai/