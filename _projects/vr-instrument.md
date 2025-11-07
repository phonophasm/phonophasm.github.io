---
title: "PhonoSPHERE — VR Sampler Instrument"
layout: default
date: 2025-11-07
tags: [VR, Unity, Music, Instrument, Quest 3, Passthrough, Audio]
# Keep the existing site theme; do not add new CSS/JS here.
---

# PhonoSPHERE — VR Sampler Instrument

*A performance-ready VR sampler for Meta Quest 3 with key/scale mapping, multi-sample layering, 8-track looping, and full-color passthrough.*

![Hero](assets/vr-instrument/hero.jpg "Live capture — replace with your hero image")

## TL;DR
PhonoSPHERE is a Unity-built VR instrument designed for live looping and expressive sampling. It lets you **map samples to musical keys and scales**, **layer multiple samples simultaneously**, and **record up to 8 loop tracks**—all inside **Quest 3 passthrough** so you can stay present with your band and audience.

---

## What it is

- **VR Sampler + Looper**  
  Trigger, pitch, and stretch samples in musical context. Capture ideas quickly with up to **8 loop tracks**.

- **Musical Intelligence**  
  **Key & scale mapping** keeps everything in tune. Pick a key, select a scale (including custom scales), and perform without clashing notes.

- **Multi-Sample Layers**  
  Stack pads/slots so **multiple samples can play simultaneously** (chords, textures, layered hits).

- **Passthrough Performance**  
  Built for **Meta Quest 3** passthrough so you can see your band, stage, and audience while performing.

- **Built for Stage**  
  Fast UI, clear feedback, minimal friction. Designed to withstand long sets.

![UI Grid](assets/vr-instrument/ui-grid.jpg "Key/Scale grid")

---

## Core Features

- **Key/Scale Mapping**: Major, minor, modes, and custom scales; per-scene or per-instrument configuration.  
- **Sample Slots & Banks**: Load multiple samples, assign to pads/notes, layer sounds.  
- **Up to 8 Loop Tracks**: Arm/record/overdub, quick clear, and visual meters.  
- **Quest 3 Passthrough**: Perform in mixed reality; align with your physical setup.  
- **Performance Controls**: Velocity-like modulation, latch/hold options, and quick mute/solo on loops.  
- **(Optional) Audio-Reactive Visuals**: Lightweight reactive elements for feedback without distracting from playability.  
- **Unity + OpenXR**: Modern XR pipeline; portable to future devices.

![Passthrough](assets/vr-instrument/passthrough.jpg "Passthrough view")
![Looper](assets/vr-instrument/looper.jpg "8-track looper UI")

---

## Short Demo Notes

- **Scenario A — Live Band:** Use passthrough to stay locked with the drummer, capture a four-bar groove, layer textures on top, and ride the loop mutes for dynamics.  
- **Scenario B — Solo Set:** Build ambient beds with layered pads, add percussive hits in a different bank, then improvise with scale-locked leads.  
- **Scenario C — Studio Sketching:** Rapidly try different keys/scales to find a vibe, commit takes into the looper, export stems later (pipeline WIP).

![Performance](assets/vr-instrument/performance.jpg "Live performance")

---

## Process (condensed)

**Goal:** An instrument that feels *musical first* in VR—quick to learn, hard to outgrow.

1) **Research & Constraints**  
   - Operating live in **MR (Quest 3 passthrough)** to reduce isolation from band/audience.  
   - Keep CPU/GPU budget low for long sets; simple, readable UI over flashy visuals.

2) **Early Prototypes**  
   - **Grid-based sampler**: pads mapped to scale degrees for instant harmony.  
   - **Looper add-on**: minimal HUD with transport states (arm/record/overdub).  
   - **Usability focus**: big hit areas, wrist-level UI when needed, reduced menus.

3) **Iteration**  
   - **Sample layering** so chords/textures are one gesture away.  
   - **Key/scale switching** with guardrails to prevent sudden dissonance mid-song.  
   - **Latent bugs from long sessions**: addressed with fixed reference frames and careful device calibration practices for stability during 60+ minute sets.

4) **Field Testing**  
   - Rehearsals and first gig trials informed control placement, loop meters, and emergency “clear/mute” ergonomics.

![Sketch](assets/vr-instrument/process-sketch.jpg "Early sketch")
![Prototype](assets/vr-instrument/process-prototype.jpg "First prototype")
![Iteration](assets/vr-instrument/process-iteration.jpg "Recent iteration")

---

## Tech Stack

- **Engine:** Unity (OpenXR)  
- **Device:** Meta Quest 3 (Passthrough)  
- **Audio:** Unity Audio/Mixer groups; scale/key mapping logic; 8-track looper system  
- **Input:** Controllers or hands (project-dependent)  
- **Build:** Android (Quest) with performance profiling & long-session stability checks

---

## Why it matters

VR instruments often sacrifice *musicality* for *novelty*. PhonoSPHERE flips this: **musical guardrails** (key/scale mapping), **looping as a compositional tool**, and **MR presence** to keep performers connected with their environment. It’s built for **real shows**, not just demos.

---

## What’s next

- Stem export & clip management
- Per-track FX and sends
- Deeper **custom scale** editor and per-pad micro-tuning
- Performance presets & setlist loader
- Expanded audio-reactive cues that stay subtle on stage

---

## Credits & Notes

- Built by **Peter Harrison** as part of ongoing research into expressive VR/MR instruments.  
- Thanks to collaborators and bandmates who stress-tested early builds during rehearsals.

---

## Gallery

![Hero](assets/vr-instrument/hero.jpg)
![UI Grid](assets/vr-instrument/ui-grid.jpg)
![Looper](assets/vr-instrument/looper.jpg)
![Passthrough](assets/vr-instrument/passthrough.jpg)
![Performance](assets/vr-instrument/performance.jpg)
![Sketch](assets/vr-instrument/process-sketch.jpg)
![Prototype](assets/vr-instrument/process-prototype.jpg)
![Iteration](assets/vr-instrument/process-iteration.jpg)

---

## Press / Demo Requests

*Interested in a demo or collab?* Reach out via the contact links on this site.
