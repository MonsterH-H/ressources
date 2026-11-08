---
name: motion-design
description: Build polished 2D motion graphics and kinetic typography with GSAP, CSS, SVG, Canvas, PixiJS or D3.
user-invocable: true
---

# Motion design craft

Use animation to direct attention, explain a relationship, reveal a sequence or establish emotion. Every movement needs purpose.

## Motion fundamentals
- Timing: hierarchy through duration, anticipation, holds and release.
- Easing: custom easing for intention; avoid linear movement except where mechanical.
- Stagger: readable sequences, not decorative noise.
- Continuity: match direction, velocity, scale and anchors across cuts.
- Overshoot: sparingly and only when the material supports it.
- Depth: scale, parallax, overlap, light and shadow consistently.
- Typography: animate line/word/character only when legibility survives.

Use GSAP for deterministic sequences, SVG for crisp paths/masks, CSS for layout, Canvas/PixiJS for many sprites and D3 for data graphics. HyperFrames hosts HTML compositions; Remotion hosts React compositions.

Video animation must be deterministic at a requested frame/time. Avoid requestAnimationFrame-only timing. Derive animation from host timeline values. Check start/end frames, flashes, off-by-one frames and late font swaps.
