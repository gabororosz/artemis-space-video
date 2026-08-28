---
workflow: faceless-explainer
flow: automation
storyboard: no
message: "Artemis II is humanity's first crewed lunar flyby in over 50 years — four astronauts riding a free-return figure-8 past the far side and home."
destination: youtube
aspect: 1920x1080
language: en
length: 60s
angle: story-explainer
narration: yes
voice: bf_emma
style_preset: broadside
---

## Intent

A cinematic 60-second explainer titled **Artemis II: Return to the Moon**. Visual identity is "Mission Control Cinematic" — dark deep-space canvas with precision data overlays, NASA flight-dynamics console language, cinematic space-documentary pacing. Audience: space-curious YouTube / embed viewers. Tone: authoritative, weighted, no bounce.

## Customizations

- Sub-compositions `scene-1.html` through `scene-7.html`.
- Shader-adjacent cinematic dissolves between scenes (~0.6s). Harness registry: `blur-crossfade 0.6s` as the primary (Tier-B injector; true WebGL shaders are deferred). One `zoom-through 0.6s` into the lunar-flyby hero.
- TTS voice `bf_emma` (Kokoro British documentary). Per-word captions, bottom-center, bone-white on void black with a subtle drop shadow.
- Deterministic data counters (seeded PRNG if needed; no `Date.now`).
- DESIGN.md is the visual-identity source of truth (palette, type, What NOT to Do) written before scene HTML.

## Notes

- Formed request + "just build it" → `flow: automation`, `storyboard: no`, derived `mode: autonomous`.
- No remembered prefs or recipes at intake.
- HeyGen unsigned at Setup; continue with local Kokoro + MusicGen.
- Do not reproduce NASA's official mission patch (restricted insignia). Invent a geometric flyby silhouette.
