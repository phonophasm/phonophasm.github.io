---
layout: default
title: "PHONOSPHERE demo — a first look"
date: 2025-11-27
tags: [PHONOSPHERE, vr, music, devlog]
---

![Welcome view of the PHONOSPHERE demo, showing the four curved grids and title card]({{ '/assets/projects/phonosphere/welcome.png' | relative_url }})

After months of building, testing, breaking, and rebuilding, I’m sharing the first public demo of **PHONOSPHERE** — a VR musical instrument designed for hand-tracked performance on the Meta Quest.

This demo is an early snapshot rather than a finished product, but it already expresses the core idea behind the project:  
making music in VR feel **physical, playful, and embodied**, using your hands and movement as the primary interface.

A download link will be added here soon when the demo goes live on SideQuest.

---

## What PHONOSPHERE is

PHONOSPHERE is built around a simple idea: **your hands and body can be the instrument**.

Instead of controllers, buttons, or traditional menus, the system relies on hand tracking and a small gesture-language developed through this project. The aim is to create a performance experience that feels expressive and intuitive — somewhere between a sampler, a synthesizer, and a reactive VR sculpture.

It’s designed to be something you *play*, explore, and gradually learn, rather than something you operate.

![Touch interaction on the curved grid layout, showing hand-tracked contact with note spheres]({{ '/assets/projects/phonosphere/touch 1.png' | relative_url }})

---

## What’s included in the demo

This first demo focuses on the essential mechanics of the PHONOSPHERE system.

### 1) Four instrument grids  
You’ll see four curved grids of note spheres placed in front of you.  
Each grid represents a different instrument sound, with its own colour theme and sonic character.

### 2) Note triggering  
Notes are played by touching spheres with your finger and thumb.  
Each sphere is mapped to a musical scale (currently in the key of D), with simple labels to help orientation.

![Finger contact on the grid with labels, illustrating how note triggering works]({{ '/assets/projects/phonosphere/touch 2.png' | relative_url }})

### 3) Gesture controls  
The demo already includes a first set of gestural interactions:

- **Finger + thumb:** Trigger notes  
- **Pinch:** Grab a note sphere and pitch-bend it  
- **Left thumb up / down:** Change octave  
- **Right thumb up / down:** Rotate note positions  
- **Scissors gesture (left or right):** Rotate tool menus  

These gestures will be explained inside the demo through an in-world instruction page.

### 4) Labels and visual modes  
By default, note labels display each note’s letter name.  
An alternative colour-based row system (black / white / colour coding) is planned and will be available as a toggle in the sphere spawner system.

### 5) UI tools  
The demo includes an early menu system for:

- Toggling labels  
- Turning instruction text on or off  
- Switching key or scale  

![In-demo radial menu showing toggles for labels and instructions]({{ '/assets/projects/phonosphere/menu.png' | relative_url }})

![Alternate menu layout showcasing additional menu positions]({{ '/assets/projects/phonosphere/menu 1.png' | relative_url }})

![Key and scale legend displayed inside the menu for quick reference]({{ '/assets/projects/phonosphere/keyscale.png' | relative_url }})

---

## How the demo works under the hood

While this is a lightweight demo, much of the core system is already in place:

- Scale-aware sphere spawning  
- Hand-tracked sound triggering  
- Pitch-bending through grabbing  
- Grid outline and grouping systems  
- Adjustable curved grid formations  
- Support for loading different sounds into each grid  
- Early audio-reactive shaders  
- Experiments with unlit, performance-safe visuals  
- Planned flashlight-style shader using head direction  

The focus at this stage is stability, clarity, and playability rather than visual complexity.

---

## What’s planned for the full release

This demo is only a starting point.  
The full version of PHONOSPHERE is planned to include:

- A full library of my own sounds  
  - Pads, textures, percussion, synths, and ambient tones designed for VR performance  
- User-loaded samples  
  - Allowing musicians and sound designers to bring their own material  
- Expanded grid layouts  
  - Adjustable spacing, rotation, and placement  
- Richer gesture-based expression  
  - More ways to shape sound through movement  
- Stronger audio-reactive visuals  
  - Shaders and effects that feel alive while you play  
- A cleaner performance mode  
  - Simplified UI for live sets or recording  
- Potential multiplayer features (long-term)  
  - Exploring shared musical spaces inside the same instrument  

Which of these ideas survive — and how they evolve — will be shaped by real use and feedback.

---

## Getting feedback

I’m releasing this demo early because I want to learn from how people actually interact with it.

If you try it, I’d love to hear:

- What feels intuitive?  
- What feels confusing or awkward?  
- Which gestures work well?  
- What would you like to see developed further?  

Feedback from this stage will directly influence the direction of the full release.

---

## Demo link coming soon

This post will be updated with:

- The SideQuest download link  
- Version notes and updates  
- Changelog and suggestions  

Thank you for taking the time to explore PHONOSPHERE and this first demo.  
I’m excited to keep refining the instrument, learning from how it’s used, and developing it into a more complete space for musical exploration.

![Closing view of the PHONOSPHERE interface with active grids]({{ '/assets/projects/phonosphere/touch 1.png' | relative_url }})
