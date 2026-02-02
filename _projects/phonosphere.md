---
title: "PHONOSPHERE — VR sampler instrument"
layout: default
date: 2025-11-07
tags: [VR, Unity, Music, Instrument, Quest 3, Passthrough, Audio]
# Keep the existing site theme; do not add new CSS/JS here.
---

# PHONOSPHERE — VR sampler instrument

*A VR sampler + looper for Meta Quest 3, exploring key/scale mapping, layered sampling, and mixed-reality performance through passthrough.*

> **Status:** Active development (work in progress). This page documents the current state of PHONOSPHERE and will evolve as the instrument develops through testing, feedback, and performance.

**Demo:** [PHONOSPHERE demo on SideQuest](https://sidequestvr.com/app/45447)

![PHONOSPHERE hero]({{ '/assets/projects/phonosphere/title list image.png' | relative_url }} "Hero capture")

PHONOSPHERE is a Unity-built VR instrument in active development, designed for live looping and expressive sampling. It explores how **key/scale mapping**, **layered samples**, and **gesture-based interaction** can support musical performance inside VR, while staying connected to the physical world through **Quest 3 passthrough**.
{: .tldr-highlight }

---

## What it is

- **VR Sampler + Looper**  
  Trigger and shape samples in a musical context, then capture ideas quickly with up to **8 loop tracks** (current build target).

- **Musical Guardrails**  
  **Key & scale mapping** keeps performances in tune. Pick a key, select a scale (including custom scales), and play without clashing notes.

- **Multi-Sample Layers**  
  Stack pads/slots so **multiple samples can play simultaneously** (chords, textures, layered hits).

- **Passthrough Performance**  
  Built for **Meta Quest 3** passthrough so you can see your band, stage, and audience while playing.

- **Built for Long Sessions**  
  Fast UI, clear feedback, minimal friction — designed with long rehearsal and performance sessions in mind.

![UI grid]({{ '/assets/projects/phonosphere/banner park.png' | relative_url }} "Key/scale grid view")

---

## Core Features (current build)

The items below reflect the current development build and may change as PHONOSPHERE evolves.

- **Key/Scale Mapping**: Major, minor, modes, and custom scales; per-scene or per-instrument configuration.  
- **Sample Slots & Banks**: Load multiple samples, assign to pads/notes, layer sounds.  
- **Looping System**: Arm/record/overdub, quick clear, and visual feedback (loop workflow actively iterating).  
- **Quest 3 Passthrough**: Perform in mixed reality; align the instrument with your physical setup.  
- **Performance Controls**: Modulation options, latch/hold behaviours, and quick mute/solo concepts for live use.  
- **(Optional) Audio-Reactive Visuals**: Lightweight reactive elements for feedback without distracting from playability.  
- **Unity + OpenXR**: Modern XR pipeline; portable foundation for future devices.

![Passthrough]({{ '/assets/projects/phonosphere/screenshot 2.png' | relative_url }} "Passthrough view")
![In-app menu]({{ '/assets/projects/phonosphere/menu 2.png' | relative_url }} "Menu view")
![Alternate menu layout]({{ '/assets/projects/phonosphere/menu 3.png' | relative_url }} "Alternate menu view")

---

## Short Demo Notes

- **Scenario A — Live Band:** Use passthrough to stay locked with the drummer, capture a groove, layer textures on top, and ride loop mutes for dynamics.  
- **Scenario B — Solo Set:** Build ambient beds with layered pads, add percussive hits in a different bank, then improvise with scale-locked leads.  
- **Scenario C — Studio Sketching:** Rapidly try different keys/scales to find a vibe, commit takes into the looper, and refine later (export pipeline WIP).

![Performance]({{ '/assets/projects/phonosphere/banner.png' | relative_url }} "Live performance")

---

## Process (condensed)

**Goal:** An instrument that feels *musical first* in VR — quick to learn, hard to outgrow.

1) **Research & Constraints**  
   - Operating live in **MR (Quest 3 passthrough)** to reduce isolation from band/audience.  
   - Keep CPU/GPU budget low for long sessions; readable UI over flashy visuals.

2) **Early Prototypes**  
   - **Grid-based sampler**: pads mapped to scale degrees for instant harmony.  
   - **Looping add-on**: minimal HUD with transport states (arm/record/overdub).  
   - **Usability focus**: big hit areas, wrist-level UI when needed, reduced menus.

3) **Iteration**  
   - **Sample layering** so chords/textures are one gesture away.  
   - **Key/scale switching** with guardrails to reduce dissonance mid-song.  
   - **Long-session stability**: attention to reference frames, calibration routines, and performance profiling.

4) **Field Testing**  
   - Rehearsals and early gig trials informing control placement, loop feedback, and emergency “clear/mute” ergonomics.

![Sketch]({{ '/assets/projects/phonosphere/screenshot 1.png' | relative_url }} "Early capture")
![Prototype]({{ '/assets/projects/phonosphere/touch 1.png' | relative_url }} "Interface contact")
![Iteration]({{ '/assets/projects/phonosphere/touch 2.png' | relative_url }} "Iteration detail")

---

## Tech Stack

- **Engine:** Unity (OpenXR)  
- **Device:** Meta Quest 3 (Passthrough)  
- **Audio:** Unity Audio/Mixer groups; scale/key mapping logic; looping system (in development)  
- **Input:** Hands and/or controllers (project-dependent)  
- **Build:** Android (Quest) with profiling and long-session stability checks

---

## Why it matters

Many VR instruments prioritise *novelty* over *musicality*. PHONOSPHERE pushes in the opposite direction: **musical guardrails** (key/scale mapping), **looping as a compositional tool**, and **MR presence** to keep performers connected with their environment. It’s designed with **real rehearsals and shows** in mind, not only demos.

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

![Hero]({{ '/assets/projects/phonosphere/title list image.png' | relative_url }})
![UI grid]({{ '/assets/projects/phonosphere/banner park.png' | relative_url }})
![Passthrough]({{ '/assets/projects/phonosphere/screenshot 2.png' | relative_url }})
![In-app menu]({{ '/assets/projects/phonosphere/menu 2.png' | relative_url }})
![Alternate menu]({{ '/assets/projects/phonosphere/menu 3.png' | relative_url }})
![Performance]({{ '/assets/projects/phonosphere/banner.png' | relative_url }})
![Sketch]({{ '/assets/projects/phonosphere/screenshot 1.png' | relative_url }})
![Prototype]({{ '/assets/projects/phonosphere/touch 1.png' | relative_url }})
![Iteration]({{ '/assets/projects/phonosphere/touch 2.png' | relative_url }})

---

## Press / Demo Requests

*Interested in a demo or collab?* Reach out via the contact links on this site.

**Support:** Visit the [PhonoSPHERE Support page]({{ '/support/' | relative_url }}) for help, issue reporting tips, and updates.
