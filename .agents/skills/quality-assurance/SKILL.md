---
name: quality-assurance
description: Review source changes for broken interactions, responsive failures, accessibility issues, and unsupported claims.
---
# Quality Assurance
- Verify cache-busted asset URLs match the committed files.
- Check every navigation anchor against a real element ID and every control against its event handler.
- Review semantics, accessible labels, focus visibility, ARIA state, and live feedback.
- Review narrow mobile, tablet, and desktop layouts for overflow and cramped controls.
- Check reduced-motion behavior, canvas fallback, visibility pause, and pixel-ratio limits.
- Search for dead links, broken selectors, accidental network submission, and unsupported claims.
- Run checks that are available and report only checks that actually ran.
- Treat commit success, workflow success, and live browser verification as separate facts.