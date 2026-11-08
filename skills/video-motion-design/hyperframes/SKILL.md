---
name: hyperframes
description: Create and render agent-driven HTML video compositions with HyperFrames CLI, CSS, SVG and GSAP.
user-invocable: true
---

# HyperFrames production

Use the current installed CLI as source of truth: run npx hyperframes help and npx hyperframes doctor before relying on flags. Official guide: https://hyperframes.app/docs/5-packages/cli

1. Initialize with npx hyperframes init using only options supported by the installed CLI.
2. Build scenes as semantic HTML/CSS/SVG. Keep scene IDs, durations and composition metadata consistent with the storyboard.
3. Add GSAP timelines and deterministic scene timing. Seed procedural effects.
4. Preview with npx hyperframes preview; run checks supported by the installed version.
5. Snapshot critical timestamps, inspect frames, correct overlaps and safe areas.
6. Render using current CLI flags; validate with FFprobe.

Install skills only through the official CLI: npx hyperframes skills --claude. Never invent CLI flags; check installed help.
