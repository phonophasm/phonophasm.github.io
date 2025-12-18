---
layout: default
title: "phonosphere demo — a first look"
date: 2025-11-27
tags: [phonosphere, vr, music, devlog]
---

![Welcome view of the phonosphere demo, showing the four curved grids and title card]({{ '/assets/projects/phonosphere/welcome.png' | relative_url }})

After months of building, testing, breaking, rebuilding, and refining, I’m finally sharing the first public demo version of **phonosphere**, my VR musical instrument designed for hand-tracked performance on the Meta Quest.

This demo is a small preview of the full vision, but it already includes the core ideas: intuitive hand-based control, curved grids of musical spheres, audio-reactive visuals, and a physical, playful approach to sound.

Thank you for visiting my website and taking an interest in what I'm creating — it truly means a lot. I’ll be updating this post soon with the download link for the demo.

## What phonosphere is about

phonosphere is a VR musical instrument created around the idea that your hands and body can be the instrument.

Instead of relying on controllers, buttons, or menus, the demo uses hand tracking and a small gesture-language we’ve developed during this project. The goal is to create a performance experience that feels expressive, immersive, and natural — something between a sampler, a synthesizer, and a reactive VR sculpture.

![Touch interaction on the curved grid layout, showing hand-tracked contact with note spheres]({{ '/assets/projects/phonosphere/touch 1.png' | relative_url }})

## What’s included in the demo

The demo focuses on the essential mechanics of the phonosphere system.

### 1) Four instrument grids
You will see four curved grids of note spheres placed in front of you. Each grid represents a different instrument sound, and each keeps its own parent colour theme.

### 2) Note triggering
You play notes by touching spheres with your finger and thumb. Each sphere is mapped to a musical scale (currently in the key of D), and each note includes a simple label for clarity.

![Finger contact on the grid with labels, illustrating how note triggering works]({{ '/assets/projects/phonosphere/touch 2.png' | relative_url }})

### 3) Gesture controls
We’ve already implemented the first version of the phonosphere gestural controls:

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

![In-demo radial menu showing toggles for labels and instructions]({{ '/assets/projects/phonosphere/menu.png' | relative_url }})

![Alternate menu layout showcasing additional menu positions]({{ '/assets/projects/phonosphere/menu 1.png' | relative_url }})

![Key scale legend displayed inside the menu for quick reference]({{ '/assets/projects/phonosphere/keyscale.png' | relative_url }})

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

The demo is only a small preview — the full phonosphere will include:

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

Thank you for checking out my website and being interested in phonosphere. I’m excited to hear your thoughts and see how you interact with this first version — and I’m looking forward to improving it and bringing the full instrument to life.

![Closing view of the phonosphere interface with active grids]({{ '/assets/projects/phonosphere/touch 1.png' | relative_url }})
