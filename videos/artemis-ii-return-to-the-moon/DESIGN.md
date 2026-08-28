---
version: 1
name: Mission Control Cinematic — Artemis II
description: >
  Dark deep-space canvas with precision data overlays. Inspired by NASA flight-dynamics
  consoles and cinematic space documentaries. Frame unit 1920×1080.
unit: the frame — 1920×1080
principle: atoms are sacred · data is chrome · motion is weighted · numbers come from the mission

colors:
  void-black: "#05070D"
  deep-navy: "#0B1426"
  bone-white: "#E8EEF7"
  ignition-orange: "#FF6B35"
  telemetry-cyan: "#4FC3F7"
  lunar-gold: "#FFD166"
  canvas: "#05070D"
  ink: "#E8EEF7"
  accent: "#FF6B35"
  accent-2: "#4FC3F7"

typography:
  display: { fontFamily: "Space Grotesk", cqw: 9.375, weight: 700, lineHeight: 0.88, tracking: "-0.03em", upper: true }
  h1:      { fontFamily: "Space Grotesk", cqw: 9.375, weight: 700, lineHeight: 0.9, tracking: "-0.03em" }
  h2:      { fontFamily: "Space Grotesk", cqw: 1.875, weight: 600, lineHeight: 1.15, tracking: "0.04em", upper: true }
  subtitle:{ fontFamily: "Space Grotesk", cqw: 1.875, weight: 500, lineHeight: 1.3, tracking: "0.02em" }
  body:    { fontFamily: "Space Grotesk", cqw: 1.2, weight: 400, lineHeight: 1.5 }
  caption: { fontFamily: "Space Grotesk", cqw: 1.15, weight: 500, lineHeight: 1.2 }
  label:   { fontFamily: "JetBrains Mono", cqw: 0.72, weight: 500, tracking: "0.12em", upper: true }
  telemetry:{ fontFamily: "JetBrains Mono", cqw: 1.1, weight: 500, tracking: "0.04em", tabular: true }
  stat:    { fontFamily: "JetBrains Mono", cqw: 2.4, weight: 700, tracking: "-0.02em", tabular: true }

spacing:
  pad-x: "5.5cqw"
  pad-y: "5.5cqw"
  gap-lg: "3.5cqw"
  gap-md: "2cqw"
  gap-sm: "1cqw"

components:
  canvas:
    background: "{colors.void-black}"
    overlay: "{colors.deep-navy} at 40% as a radial swell, never a full-screen linear gradient"
  starfield:
    description: "Subtle parallax starfield on every scene. Seeded PRNG (mulberry32). Finite GSAP travel, never repeat:-1."
  telemetry-rail:
    font: "{typography.label}"
    color: "{colors.telemetry-cyan}"
    description: "Timestamps, coordinates, T+, distances. tabular-nums. JetBrains Mono only."
  stat-card:
    border: "1px solid {colors.telemetry-cyan} at 35%"
    background: "{colors.deep-navy} at 72%"
    accent: "{colors.ignition-orange}"
    description: "Mission-console card. Sharp corners. No drop-shadow blobs."
  caption-rail:
    color: "{colors.bone-white}"
    ground: "{colors.void-black}"
    shadow: "0 2px 12px rgba(5,7,13,0.85)"
    placement: "bottom-center overlay — not a reserved keep-out band"
---

# Overview

Mission Control Cinematic. The frame is a flight-dynamics console floating in deep space: void black ground, bone-white type, ignition orange as scarce voltage, telemetry cyan as the data voice, lunar gold for the one hero number.

# The Frame

1920×1080. True vertical center at y = 540. Captions overlay the bottom-center; do not shift content up to make room. Courtesy: do not park critical small readable text in the bottom ~80px center span.

# Type

- **Space Grotesk** — titles, headings, subtitle, spoken-caption rail.
- **JetBrains Mono** — telemetry, coordinates, timestamps, distances, Δv, T+, tabular counters.
- Hero title "ARTEMIS II" at 180px. Subtitle at 36px. Data counters `font-variant-numeric: tabular-nums`.

# Motion

Weighted only: `power3.out`, `expo.out`, `power2.inOut` on dissolves. No bounce. No elastic. No idle sine wobble. Starfield parallax is a finite, seeded travel — not a breathe loop.

# What NOT to Do

- No generic blues (no `#1E90FF`, no Material blue, no default-AI purple-blue gradients).
- No Roboto, Inter, Arial, or system-ui as the designed face.
- No bouncy easing (`bounce`, `elastic`, `back.out` overshoot as a default).
- No full-screen linear gradients on dark backgrounds. Ground is void black; navy is a radial swell or a panel, never a top-to-bottom wash.
- No NASA official insignia / mission-patch artwork (restricted). Invent a geometric silhouette.
- No `Date.now()`, unseeded `Math.random()`, or `repeat: -1`.
- No Google Fonts `<link>` at render time — local `@font-face` only.
- No narration sentences restated as on-screen body copy. Designed chrome (titles, telemetry, crew plate) is content, not captions.
