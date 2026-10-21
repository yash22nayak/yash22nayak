# GitHub Profile README — Creative Redesign Plan

## Concept
**Ambient Pixel Universe × Hacker Command Center**

The profile should feel like a miniature developer operating system inside a pixel-art purple universe—not a generic developer banner, contribution graph, or row of badges.

## Visual direction
- Custom pixel-art space scene with aubergine background and a subtle pixel grid.
- Terminal identity panel on the left with Yash's name and engineering focus.
- Pixel planet, orbital paths, tiny satellite, workstation and robot assistant on the right.
- Ambient animated stars, a blinking terminal cursor and small telemetry indicator.
- Palette: near-black violet, aubergine, purple, lavender and pale lilac highlights.
- The design's personality comes from the scene and composition, not from more badges.

## Files
- `README.md`: profile story, skills, system map, selected work and links.
- `assets/ambient-purple.svg`: custom 1200×430 pixel-universe hero.
- `PROFILE-README-PLAN.md`: this plan.

## Technical constraints
- GitHub README cannot execute arbitrary JavaScript; no real command execution or cursor-reactive effects.
- GitHub may sanitize or not animate SVG SMIL. The SVG is intended to remain visually useful as a static image if animation is disabled.
- If animation fails in the actual GitHub render, use an optimized GIF/APNG for the hero while keeping meaningful text in Markdown.
- Check mobile cropping and SVG rendering before merging.

## Validation checklist
1. Preview the SVG directly on GitHub and inside the README.
2. Verify animation behavior after GitHub sanitization.
3. Check small-screen layout and alt text.
4. Check every project link before publishing.
5. Merge only after reviewing the feature branch diff.
