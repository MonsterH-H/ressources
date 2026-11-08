---
name: remotion
description: Create frame-accurate video compositions and edit media with React and Remotion using official best practices.
user-invocable: true
---

# Remotion production

Use the official Claude Code plugin and Remotion Agent Skills as authority for current APIs: https://www.remotion.dev/docs/ai/claude-code-plugin and https://www.remotion.dev/docs/ai/skills

Start from the blank template when full control is needed:

```bash
npx create-video@latest --yes --blank project-name
cd project-name
npx remotion skills add
npm run dev
```

Use Composition, Sequence, AbsoluteFill, Video, Audio, Img, staticFile, interpolate and spring only as documented in the installed version. Derive timing from useCurrentFrame() and useVideoConfig(). Use Sequence for time-based layers; avoid CSS animations that are not frame-deterministic.

Use current official APIs for audio, captions and 3D. Render with the project's documented script or npx remotion render; validate MP4 with FFprobe. Check Remotion's current license and automation terms before commercial use.
