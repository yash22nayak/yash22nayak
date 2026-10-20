# GitHub Profile README — Implementation Plan

## Goal
Refresh @yash22nayak with an ambient purple dot/constellation identity: understated, distinctive, and aligned with backend engineering, security, and automation.

## Existing profile audit
- Profile repository: https://github.com/yash22nayak/yash22nayak
- Existing README describes Laravel/PHP, Livewire, Tailwind CSS, MySQL, security/VAPT, Chrome extensions, automation, and AI/product interests.
- Keep the technical identity, but make the first screen more visual and scan-friendly.
- Keep private projects private; link only to public repositories.

## Design decisions
1. **Hero:** self-contained 1200×300 SVG with dark aubergine gradient, thin constellation links, glowing purple dots, and gentle SMIL pulsing.
2. **Content:** compact whoami, interests, toolkit, selected public work, and contact links.
3. **Palette:** near-black violet (#0b0714), deep aubergine (#130b24), purple (#8b5cf6), lavender (#c4b5fd).
4. **Motion:** slow ambient opacity/radius changes; no cursor-tracking or JavaScript.
5. **Compatibility:** important text remains Markdown. The SVG has a static fallback if animation is not rendered.
6. **Privacy:** no private repository links, personal contact details, or claims about live status.

## Files
- `README.md` — profile layout and content.
- `assets/ambient-purple.svg` — animated constellation hero.

## Apply and validate
1. Review the branch diff and verify SVG/Markdown paths.
2. Confirm the hero loads on GitHub; if SVG animation is stripped, keep the static image or convert the artwork to a GIF.
3. Check both light and dark GitHub themes and narrow mobile rendering.
4. Merge the branch when approved. GitHub profile READMEs cannot run arbitrary JavaScript, so pointer-reactive dots require a separate hosted website.
