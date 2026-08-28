---
format: 1920x1080
duration: 60s
message: "Artemis II is humanity's first crewed lunar flyby in over 50 years — four astronauts riding a free-return figure-8 past the far side and home."
arc: story-explainer
audience: space-curious YouTube viewers
mode: autonomous
music: cinematic dark space documentary, sparse low strings, distant pads, no vocals, slow tension
---

## Frame 1 — Title Card

- status: animated
- src: compositions/frames/scene-1.html
- duration: 8s
- poster: 4s
- transition_in: cut
- scene: ARTEMIS II over a mission-patch silhouette on a void-black starfield
- voiceover: "April first, twenty twenty-six. Artemis Two. The first crewed lunar flyby in over fifty years."
- type: hook
- persuasion: Stakes / consequence + concept announcement
- beat: Intrigue + gravity
- blueprint: titlecard-reveal (Adapt)
- focal: the ARTEMIS II wordmark
- roles: ARTEMIS II = foreground subject · patch silhouette = supporting · starfield = background · datetime stamp = supporting
- sfx: whoosh-short
- asset_candidates:

narrativeRole: Open on the mission name and the fifty-year gap so the viewer knows why this launch matters before any mechanics.
keyMessage: Artemis II is the first crewed lunar flyby in over fifty years.

Adapt: keep the one-restrained-reveal + hold; drop Broadside lowercase-only so ARTEMIS II can sit at 180px uppercase. Starfield parallax (seeded) is the live hold, not a breathe loop.

Scene 1 (0.0–1.4s): void-black full-bleed clip + seeded starfield (layered-depth). Geometric patch silhouette (crescent + figure-8, not NASA insignia) fades in centered, dim ~35%.
Scene 2 (1.4–3.6s): ARTEMIS II at 180px Space Grotesk 700, bone-white, Centered ~50% of frame — gentle fade-in + scale 0.96→1, power3.out. → scale-swap-transition (restrained settle)
Scene 3 (3.6–5.8s): subtitle "First Crewed Lunar Flyby in Over 50 Years" at 36px reveals under the title as the VO names the gap. → discrete-text-sequence
Scene 4 (5.8–8.0s): JetBrains Mono stamp "APR 01 2026 · 22:35 UTC · KSC LC-39B" seats bottom-left (courtesy off the caption overlay). Starfield finite parallax continues. Hold.

## Frame 2 — Launch + High Earth Orbit

- status: animated
- src: compositions/frames/scene-2.html
- duration: 8s
- poster: 4s
- transition_in: blur-crossfade 0.6s
- scene: SLS silhouette with exhaust plume and a live telemetry ticker
- voiceover: "The Space Launch System lifts Orion into a high elliptical Earth orbit. Twenty-four hours of system checkouts before they leave home."
- type: product_intro
- persuasion: Signposting + demonstration
- beat: Orientation + momentum
- blueprint: dataviz-countup (Adapt)
- focal: SLS rocket silhouette + exhaust
- roles: rocket = foreground subject · telemetry ticker = supporting · starfield = background
- sfx: whoosh-cinematic, ping
- asset_candidates:

narrativeRole: Name the vehicle and the first phase so the mission has a body, not just a title.
keyMessage: SLS puts Orion into a ~24h high elliptical Earth orbit for checkouts.

Adapt: keep the count-up as the data spine; the hero is the rocket, not a ring. Telemetry (altitude, velocity, T+) ticks while the plume draws.

Scene 1 (0.0–1.6s): heading "PHASE 01 · LAUNCH + HIGH EARTH ORBIT" in JetBrains Mono cyan, rule-of-thirds left. Rocket SVG silhouette seats lower-center. → dynamic-content-sequencing
Scene 2 (1.6–4.4s): exhaust plume SVG self-draws in ignition orange; rocket holds. Telemetry ticker (altitude km, velocity km/s, T+) starts counting. → svg-path-draw + counting-dynamic-scale
Scene 3 (4.4–6.6s): annotation "~24h elliptical orbit for system checkouts" fades in as the VO names checkouts. → discrete-text-sequence
Scene 4 (6.6–8.0s): counters hold at cruise values. Starfield parallax. No exit.

## Frame 3 — Trans-Lunar Injection

- status: animated
- src: compositions/frames/scene-3.html
- duration: 8s
- poster: 4s
- transition_in: blur-crossfade 0.6s
- scene: Earth–Moon free-return arc drawn in cyan with a TLI burn marker
- voiceover: "Then the trans-lunar injection burn. Six minutes. A free-return trajectory, locked toward the Moon."
- type: feature_showcase
- persuasion: Progressive disclosure + causal chain
- beat: Comprehension + anticipation
- blueprint: compose
- focal: the cyan free-return trajectory
- roles: trajectory = foreground subject · Earth/Moon nodes = supporting · Δv card = supporting · starfield = background
- sfx: whoosh-short
- asset_candidates:

narrativeRole: Show the burn that leaves Earth — the mechanism that makes the flyby possible.
keyMessage: A six-minute TLI burn puts Orion on a free-return path to the Moon.

Scene 1 (0.0–1.5s): Earth disc left, Moon disc right, labeled, on void-black (split-screen / diagram). Heading empty.
Scene 2 (1.5–4.2s): cyan free-return curve draws via stroke-dashoffset from Earth toward the Moon. Label "TRANS-LUNAR INJECTION BURN · 6 MIN" with a small flame mark at the burn point, on the spoken "burn / six minutes". → svg-path-draw
Scene 3 (4.2–6.4s): stat card "Δv: +3.05 km/s" seats lower-right, count-up the 3.05. → counting-dynamic-scale
Scene 4 (6.4–8.0s): trajectory holds fully drawn. Starfield parallax. No exit.

## Frame 4 — Outbound Coast

- status: animated
- src: compositions/frames/scene-4.html
- duration: 8s
- poster: 4s
- transition_in: blur-crossfade 0.6s
- scene: Orion wireframe drifting; EARTH → MOON progress bar; distance counting down
- voiceover: "Four days outbound. Orion coasts across three hundred eighty-four thousand kilometers of empty space."
- type: feature_showcase
- persuasion: Concretization + statistical proof
- beat: Fascination + scale
- blueprint: dataviz-countup (Adapt)
- focal: distance counter + progress bar
- roles: Orion wireframe = foreground subject · progress bar = supporting · earthrise disc = supporting · starfield = background
- sfx: ping
- asset_candidates:

narrativeRole: Make the distance tangible — four days and 384,000 km of coast.
keyMessage: The outbound coast is four days across 384,000 kilometers.

Adapt: count-down (not up) on distance; progress bar is the paired graphic.

Scene 1 (0.0–1.8s): faint earthrise disc left; Orion wireframe enters from left, drifting right (asymmetric 60/40). → svg-path-draw (wireframe)
Scene 2 (1.8–5.2s): progress bar "EARTH → MOON" fills left-to-right; distance counter 384,000 km counting (tabular-nums) as VO names the kilometers. → stat-bars-and-fills + counting-dynamic-scale
Scene 3 (5.2–8.0s): bar holds near-full; Orion continues a finite drift. Starfield. No exit.

## Frame 5 — Lunar Flyby

- status: animated
- src: compositions/frames/scene-5.html
- duration: 10.432s
- poster: 6s
- transition_in: zoom-through 0.6s
- scene: Full-frame Moon; far-side closest-approach marker; crew plate Wiseman · Glover · Koch · Hansen
- voiceover: "April sixth. Closest approach: six thousand five hundred forty-five kilometers from the lunar far side. The farthest humans have ever traveled. Wiseman. Glover. Koch. Hansen."
- type: benefit_highlight
- persuasion: Statistical proof + distillation
- beat: Awe + "aha"
- blueprint: compose
- focal: the Moon + closest-approach marker
- roles: Moon = foreground subject · trajectory arc = supporting · approach marker = supporting · crew plate = supporting · starfield = background
- sfx: impact-bass-1
- asset_candidates:

narrativeRole: Land the hero fact — farthest humans have ever traveled — and name the four crew.
keyMessage: Closest approach is 6,545 km on April 6; 406,771 km from Earth, the farthest humans have gone.

Scene 1 (0.0–2.0s): full-frame cratered Moon (layered-depth, Centered). Slow camera push. → multi-phase-camera
Scene 2 (2.0–4.6s): cyan trajectory arc sweeps behind the far side. Pulsing marker "CLOSEST APPROACH · APR 06 2026 · 6,545 km" on the spoken distance. → svg-path-draw + asr-keyword-glow
Scene 3 (4.6–7.2s): secondary stat "DISTANCE FROM EARTH · 406,771 KM — FARTHEST HUMANS HAVE EVER TRAVELED" in lunar gold. Stillness before the names (0.4s). → counting-dynamic-scale
Scene 4 (7.2–10.0s): crew plate "Wiseman · Glover · Koch · Hansen" fades in. Hold. No exit.

## Frame 6 — Return Coast

- status: animated
- src: compositions/frames/scene-6.html
- duration: 8s
- poster: 4s
- transition_in: blur-crossfade 0.6s
- scene: Figure-8 completing; FREE-RETURN heading; re-entry velocity climbing to 11 km/s
- voiceover: "Gravity brings them home. The free-return arc completes. Re-entry at eleven kilometers per second."
- type: feature_showcase
- persuasion: Callback + causal chain
- beat: Inevitability + momentum
- blueprint: dataviz-countup (Adapt)
- focal: re-entry velocity counter
- roles: figure-8 trajectory = foreground subject · velocity counter = supporting · starfield = background
- sfx: whoosh-short
- asset_candidates:

narrativeRole: Mirror the outbound — the same free-return geometry is what brings them home.
keyMessage: The free-return trajectory completes; re-entry approaches 11 km/s.

Adapt: Scene 4 reversed. Count-up to 11 km/s is the signature.

Scene 1 (0.0–1.8s): heading "FREE-RETURN · GRAVITY BRINGS THEM HOME". Partial figure-8 already drawn (callback to Scene 3).
Scene 2 (1.8–5.0s): remaining arc draws to complete the 8. Velocity counter climbs toward 11 km/s as VO names re-entry. → svg-path-draw + counting-dynamic-scale
Scene 3 (5.0–8.0s): 11.0 km/s holds. Starfield. No exit.

## Frame 7 — Splashdown

- status: animated
- src: compositions/frames/scene-7.html
- duration: 10s
- poster: 6s
- transition_in: blur-crossfade 0.6s
- scene: Dawn Pacific horizon, Orion under three parachutes, mission-complete lockup
- voiceover: "Ten days. One flyby. Four astronauts. Infinite ambition. Next: Artemis Three. Boots on the Moon."
- type: cta
- persuasion: Rule of three + distillation + callback
- beat: Satisfaction + resolve
- blueprint: titlecard-reveal (Adapt)
- focal: the final stat block then the NEXT: ARTEMIS III line
- roles: parachute lockup = foreground subject · ocean horizon = background · stat block = supporting · next-title = supporting
- sfx: impact-bass-2
- asset_candidates:

narrativeRole: Close the mission and point to Artemis III — boots on the Moon.
keyMessage: Ten days, one flyby, four astronauts; next is Artemis III.

Adapt: card-chain — stat block, then mission-complete, then fade to the next-mission line (final-frame exit allowed).

Scene 1 (0.0–2.2s): dawn Pacific band (deep navy → void, NOT a full-screen linear wash — a horizon strip). Orion + three parachutes SVG. → svg-path-draw
Scene 2 (2.2–5.4s): stat block "10 DAYS · 1 FLYBY · 4 ASTRONAUTS · ∞ AMBITION" staggered per-word as VO enumerates. → kinetic-beat-slam
Scene 3 (5.4–7.6s): "APR 11 2026 · PACIFIC OCEAN · MISSION COMPLETE" lockup. Hold 0.4s.
Scene 4 (7.6–10.0s): fade to black on "NEXT: ARTEMIS III — BOOTS ON THE MOON". This is the only exit.

## Video direction

Film current: LEFT (phase sequence as forward mission time). Primary seam: blur-crossfade 0.6s. Accent: zoom-through 0.6s into Frame 5 (the flyby is ARRIVAL — Z forward). Carriers: starfield + cyan trajectory language + JetBrains telemetry chrome. Sustained-motion routes: Frame 1 staged reveals; Frame 2–4/6 sequenced UI life (counters, bars, path-draw); Frame 5 camera with intent; Frame 7 staged reveals then fade. No idle wobble. Stillness-before-climax on Frame 5 before the crew names. Captions overlay bottom-center; compose around y = 540.
