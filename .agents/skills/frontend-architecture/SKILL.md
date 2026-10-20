---
name: frontend-architecture
description: Build reliable, maintainable, dependency-light frontend experiences with semantic structure and resilient progressive enhancement.
---
# Frontend Architecture

- Prefer semantic HTML landmarks, one primary H1, ordered heading levels, real links for navigation, and buttons for actions.
- Keep CSS tokens centralized in :root; use clear component naming and mobile-first responsive overrides.
- Keep JavaScript dependency-free for this static site. Query elements once, group stateful behaviors, and keep event wiring organized by feature.
- Make content and navigation useful without canvas or animation. JavaScript should enhance, never gate, the core message.
- Avoid unsafe HTML injection. Use textContent, createElement, and explicit attributes for user-entered content.
- Bound rendering cost, cap device pixel ratio, avoid needless layout reads, and pause continuous animation when the tab is hidden.
- Cache-bust asset URLs on each deploy-worthy change so browser caches do not mask updates.
- Before committing, inspect selectors against HTML, check broken anchors, syntax, responsive states, and console errors where browser testing is available.