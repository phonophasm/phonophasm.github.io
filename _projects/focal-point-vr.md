---
layout: default
title: "Focal Point — Searching with Senses in 2D & VR"
permalink: /projects/focal-point-vr/
---

# Focal Point — Searching with Senses in 2D & VR

An interactive audiovisual experiment that asks: *how does the medium change the way we search, focus, and feel immersed?*

![Hero artwork showing the focal point glowing within layered gradients](/assets/images/focal-point.png)

Focal Point is a two-part project comparing a **projected depth-camera environment** and a **VR headset environment**, each built around the same core mechanic: using sound and abstract visuals to search for a hidden focal point. The work explores immersion, body movement, and sensory feedback, supported by a small user study comparing how people experience “searching” across both mediums.
{: .tldr-highlight }

---

## Overview

Focal Point grew out of a desire to move beyond mouse-and-keyboard interaction into more embodied, sensory ways of navigating digital spaces.

At its core:

- You guide a small **cursor/ball** using your body.
- Abstract sound and visuals react to your distance from a **focal point**.
- As you move closer, distractions reduce; as you move away, they intensify.
- The experience exists in **two versions**:
  - a **Projected (Kinect) Environment**, and
  - a **Virtual Reality Environment**.

This dual setup creates a direct comparison between **shared-space projection** and **fully immersive VR**, using the same conceptual rules.

![Diagram of the staged searching experience showing how audio and visuals guide the user toward the goal](/assets/projects/Focal-Point/searching.png)

### The searching experience

Participants begin each stage surrounded by layers of motion and sound that intentionally obscure the focal point. As they move:

- **Audio cues** shift from diffuse drones to single tones, revealing proximity and direction.
- **Visual cues** calm from turbulent noise to clean gradients when the focal point is near.
- **Haptic memory** develops as participants learn how far to reach or rotate to maintain alignment.

Each stage introduces a new obstacle—offset focal points, moving distractions, or vertical depth—so the act of searching becomes an iterative process of tuning senses, rather than a single puzzle to solve.

---

## Concept

The project treats the mind as a noisy landscape of overlapping thoughts—colour, motion, tone—through which we search for clarity.

Key ideas:

- **Searching as experience** – The process of exploring is more important than “winning”.
- **Sensory guidance** – Audio tone and visual intensity guide you toward or away from the focal point.
- **Embodied interaction** – Hands and body movement replace traditional interfaces to create a tighter loop between motion, perception, and feedback.
- **Medium comparison** – Same concept, different tools, to see how environment and embodiment change engagement.

---

## Version 1 — Projected Environment (Depth Camera)

Participants stand in front of a projected wall; a depth camera tracks their hand and moves a white ball across the screen.

As they search:

- **Visuals**: abstract shapes, shifting colour fields, increasing calmness near the focal point.
- **Audio**: a single evolving tone changes pitch/character with proximity.
- **Interaction**: crossing a threshold on the floor “enters” the environment; body movement drives the search.

This version is:

- Easy to understand and more accessible in a public/exhibition space.
- Less immersive than VR, but strong for shared, observable interaction.

![Participant using body movement to navigate the Kinect-projected searching space](/assets/projects/Focal-Point/kinect.png)

![Concept artwork from the Kinect version showing layered light guiding the focal point](/assets/projects/Focal-Point/focal-point-art.jpg)

---

## Version 2 — Virtual Reality Environment (Quest 2 + Unity)

The VR version rebuilds the same searching rules inside a fully 3D environment.

- **Platform**: Unity + Meta Quest 2 (hand tracking).
- **Interaction**: a virtual ball attached to the user’s hand by an “invisible string” moves through 360° space.
- **Visuals**: immersive abstract environments, particles, grids, and stages that evolve as users progress.
- **Audio**: positional and proximity-based tones guide users through the search.

This version:

- Feels **more immersive, embodied, and game-like**.
- Demands more orientation and adaptation but creates a stronger sense of presence and connection.

![Concept art from the VR version, showing layered grids and particles around the focal point](/assets/projects/Focal-Point/VR-art.png)

---

## Comparative Study

A small user study invited participants to try **both** versions.

Approach:

- Randomised order (coin flip) to reduce bias.
- Post-experience **survey** (Likert scales) and **semi-structured interviews**.
- Analysis of:
  - searching difficulty,
  - sense of involvement,
  - connection between body and AV feedback,
  - satisfaction when finding the focal point.

Interview transcripts were thematically coded, and keyword clustering highlighted the concepts participants repeated most often: orientation, immersion, and the importance of audio as an anchor when visual distractions increased. These findings fed back into stage design tweaks for both mediums.

Key findings (summarised):

- **Projected version**:
  - Perceived as easier to understand.
  - Good for simple, immediately legible interaction.
- **VR version**:
  - Rated higher for immersion, bodily connection, and overall satisfaction.
  - Encouraged more movement and a stronger feeling of “being inside” the search.
- **Across both**:
  - Participants enjoyed **exploration** more than simply “solving” the task.
  - Confusion + multiple paths (when intentional) can deepen engagement.

![Keyword diagram highlighting interview themes such as “immersion”, “orientation”, and “audio as guide”](/assets/projects/Focal-Point/interviews.png)

---

## Tools & Implementation

- **Projected Environment**
  - Processing 4 (Java)
  - Kinect depth camera (OpenKinect)
  - Minim (audio)
  - Single-user interaction in a shared visual space

- **VR Environment**
- Unity
  - Meta Quest 2 with hand tracking
  - C# scripts recreating the focal point logic
  - Spatialised audio and 360° abstract environments

---

## Why Focal Point Matters

Focal Point acts as a **bridge project** between interactive art and research:

- Tests how different mediums shape perception, immersion, and sensory searching.
- Informs later work on **VR instruments**, **immersive focus tools**, and potential **stress/attention regulation environments**.
- Provides a practical framework for comparing modalities when designing embodied, audio-visual experiences.

---

## What’s Next

Future development directions:

- Extend levels to emphasise exploration and flow over “correct answers”.
- Refine audiovisual behaviour for broader comfort and accessibility.
- Integrate biometric/biofeedback data (e.g. heart rate, breathing) as part of the searching logic.
- Reuse insights and codebase as foundations for new VR instruments and research prototypes.

