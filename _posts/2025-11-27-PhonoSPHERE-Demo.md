---
layout: default
title: "PhonoSPHERE Demo — A First Look"
date: 2025-11-27
tags: [phonosphere, vr, music, devlog]
---

![Header — PhonoSPHERE Demo]({{ '/assets/posts/phonosphere-demo/header-placeholder.jpg' | relative_url }} "Replace with a banner-style header image")

After months of building, testing, breaking, rebuilding, and refining, I’m finally sharing the first public demo version of **PhonoSPHERE**, my VR musical instrument designed for hand-tracked performance on the Meta Quest.

This demo is a small preview of the full vision, but it already includes the core ideas: intuitive hand-based control, curved grids of musical spheres, audio-reactive visuals, and a physical, playful approach to sound.

Thank you for visiting my website and taking an interest in what I'm creating — it truly means a lot. I’ll be updating this post soon with the download link for the demo.

## What PhonoSPHERE is about

PhonoSPHERE is a VR musical instrument created around the idea that your hands and body can be the instrument.

Instead of relying on controllers, buttons, or menus, the demo uses hand tracking and a small gesture-language we’ve developed during this project. The goal is to create a performance experience that feels expressive, immersive, and natural — something between a sampler, a synthesizer, and a reactive VR sculpture.

![Sphere grids]({{ '/assets/posts/phonosphere-demo/sphere-grids-placeholder.jpg' | relative_url }} "Replace with a GIF or screenshot of the sphere grids")

## What’s included in the demo

The demo focuses on the essential mechanics of the PhonoSPHERE system.

### 1) Four instrument grids
You will see four curved grids of note spheres placed in front of you. Each grid represents a different instrument sound, and each keeps its own parent colour theme.

### 2) Note triggering
You play notes by touching spheres with your finger and thumb. Each sphere is mapped to a musical scale (currently in the key of D), and each note includes a simple label for clarity.

### 3) Gesture controls
We’ve already implemented the first version of the PhonoSPHERE gestural controls:

- **Finger + thumb:** Trigger notes
- **Pinch:** Grab a note sphere and pitch bend it
- **Left thumb up/down:** Change octave
- **Right thumb up/down:** Rotate note positions (rotate the spheres)
- **Scissors gesture (left/right):** Rotate tool menus

These gestures will be documented inside the demo with a new hand-pose instruction page.

### 4) Labels & visual modes
Currently, labels show each note’s letter name. We also discussed adding a colour / black / white alternating row system, and this option will soon be available as a toggle in the sphere spawner script.

### 5) UI tools
The demo includes the early version of the menu system where you can toggle labels, turn instruction text on/off, and switch the key or scale.

![UI mock]({{ '/assets/posts/phonosphere-demo/ui-placeholder.jpg' | relative_url }} "Replace with a UI screenshot")

## How the demo works under the hood

A lot of the core system is already implemented:

- Sphere spawner that maps scales to sphere layout
- Sound triggers using hand-tracked interactions
- Pitch bending via grabbing
- Outline systems for instrument grids
- Adjustable curved formations
- Support for loading multiple sounds into different grids
- Early audio-reactive shaders
- Planned flashlight-style shader using head direction
- Performance-safe unlit shader experiments

This demo is intentionally lightweight but already functional for live experimentation.

## What’s coming in the full version

The demo is only a small preview — the full PhonoSPHERE will include:

- A full library of my own sounds
  - Pads, textures, percussion, synths, ambient tones — all built for VR performance.
- The ability for users to load their own samples
  - A major feature for musicians, VJs, and sound designers.
- More instrument grids and custom layouts
  - Including adjustable spacing, rotation, and orientation.
- Expanded gesture-based expression
  - More ways to interact with sound using natural movements.
- Stronger audio-reactive visuals
  - Shaders and effects that feel alive while you play.
- Cleaner performance mode
  - A simplified interface for live shows or recording.
- Potential multiplayer mode (long-term)
  - Imagine jamming with someone else inside the same sphere system.

## Getting feedback

I’m releasing this demo because I genuinely want to hear what people think.

- What feels intuitive?
- What feels confusing?
- Which gestures work well?
- What would you like to see in the full version?

Your feedback will directly influence the final instrument.

## Download link coming soon

I will update this post with:

- Demo download link
- Version updates
- Suggestions and changelog

Thank you for checking out my website and being interested in PhonoSPHERE. I’m excited to hear your thoughts and see how you interact with this first version — and I’m looking forward to improving it and bringing the full instrument to life.

![Footer — PhonoSPHERE Demo]({{ '/assets/posts/phonosphere-demo/footer-placeholder.jpg' | relative_url }} "Replace with a footer image or logo")

---

### Image notes (replace these placeholders)
- `assets/posts/phonosphere-demo/header-placeholder.jpg` — banner-style header image
- `assets/posts/phonosphere-demo/sphere-grids-placeholder.jpg` — GIF or screenshot of sphere grids
- `assets/posts/phonosphere-demo/ui-placeholder.jpg` — UI screenshot
- `assets/posts/phonosphere-demo/footer-placeholder.jpg` — footer image or logo
