---
layout: default
title: "Focal Point — Searching with Senses in 2D & VR"
permalink: /projects/focal-point-vr/
---

# Focal Point — Searching with Senses in 2D & VR

*An interactive audiovisual project exploring how different mediums shape the way we search, focus, and feel immersed.*

> **Status:** Completed exploratory project. This page documents Focal Point as a finished comparison study and a conceptual bridge toward later immersive work.

![Hero artwork showing the focal point glowing within layered gradients](/assets/images/focal-point.png)

Focal Point is a two-part project comparing a **projected depth-camera environment** and a **virtual reality environment**, each built around the same core mechanic: searching for a hidden focal point using sound, abstract visuals, and body movement.

By placing the same experience logic in two different mediums, the project explores how **immersion**, **embodiment**, and **sensory feedback** influence attention and the act of searching.
{: .tldr-highlight }

---

## Overview

Focal Point grew from a desire to move beyond mouse-and-keyboard interaction toward more **embodied, sensory ways of navigating digital spaces**.

At its core:

- Participants guide a small **cursor / ball** using their body.
- Abstract sound and visuals respond continuously to distance from a **focal point**.
- As users move closer, distractions soften; as they move away, they intensify.
- The experience exists in **two parallel versions**:
  - a **Projected Environment** using a depth camera, and  
  - a **Virtual Reality Environment** using a head-mounted display.

This dual setup allows for a direct comparison between **shared, observable interaction** and **fully immersive VR**, while keeping the conceptual rules consistent.

![Diagram of the staged searching experience showing how audio and visuals guide the user toward the goal](/assets/projects/Focal-Point/searching.png)

---

## The searching experience

Participants begin each stage surrounded by layered motion and sound that intentionally obscure the focal point. As they move:

- **Audio cues** shift from diffuse drones to clearer tones, indicating proximity and direction.
- **Visual cues** calm from turbulence to clean gradients as alignment improves.
- **Bodily memory** develops as participants learn how far to reach, rotate, or lean to stay oriented.

Each stage introduces new conditions — offset targets, moving distractions, or vertical depth — so searching becomes an ongoing process of **tuning the senses**, rather than solving a single puzzle.

---

## Concept

The project treats the mind as a noisy landscape of overlapping thoughts — colour, motion, tone — through which we search for clarity.

Key ideas include:

- **Searching as experience**  
  The act of exploration matters more than reaching an endpoint.

- **Sensory guidance**  
  Sound and visual intensity act as navigational signals rather than explicit instructions.

- **Embodied interaction**  
  Hands and body movement replace traditional interfaces, tightening the loop between action and perception.

- **Medium comparison**  
  Identical logic across different environments reveals how context and embodiment shape engagement.

---

## Version 1 — Projected environment (depth camera)

Participants stand in front of a projected wall while a depth camera tracks their hand, moving a white ball across the surface.

As they search:

- **Visuals** shift through abstract shapes, colour fields, and layered gradients.
- **Audio** evolves as a single tone whose character changes with proximity.
- **Interaction** begins when participants step into the tracked space; body movement drives navigation.

This version is:

- Immediately legible and accessible in exhibition settings.
- Less immersive than VR, but effective as a shared, observable experience.

![Album artwork used in the depth-camera installation, showing layered colours around the focal point](/assets/projects/Focal-Point/focal-point-art.jpg)
![Participant using body movement to navigate the projected searching space](/assets/projects/Focal-Point/kinect.png)

---

## Version 2 — Virtual reality environment (Quest 2 + Unity)

The VR version recreates the same searching rules inside a fully three-dimensional space.

- **Platform:** Unity + Meta Quest 2 (hand tracking).
- **Interaction:** A virtual ball attached to the user’s hand via an “invisible string” moves freely through 360° space.
- **Visuals:** Immersive abstract environments, particles, grids, and evolving stages.
- **Audio:** Spatialised tones respond to position and distance from the focal point.

This version:

- Feels more immersive and bodily engaging.
- Requires greater orientation and adaptation.
- Produces a stronger sense of presence and connection to the task.

![Participant wearing a headset inside the VR version, reaching toward the focal point](/assets/projects/Focal-Point/Focal-Point-VR.png)
![Concept art from the VR version, showing layered grids and particles around the focal point](/assets/projects/Focal-Point/VR-art.png)

---

## Comparative study

A small comparative study invited participants to experience **both versions**.

**Method (summarised):**
- Randomised order to reduce bias.
- Post-experience surveys (Likert scales) and semi-structured interviews.
- Focus on:
  - perceived difficulty,
  - sense of immersion,
  - body–feedback connection,
  - satisfaction with the searching process.

![Participants standing in front of the projection wall during the comparative study](/assets/projects/Focal-Point/participants.png)

Interview transcripts were thematically coded, revealing recurring concepts such as **orientation**, **immersion**, and **audio as an anchor** when visual information became overwhelming.

**Key observations:**
- **Projected version**
  - Easier to understand and immediately approachable.
  - Well suited to public or social spaces.
- **VR version**
  - Rated higher for immersion and bodily connection.
  - Encouraged more movement and stronger presence.
- **Across both**
  - Participants valued exploration over “winning”.
  - Intentional ambiguity and multiple paths increased engagement.

![Keyword diagram highlighting interview themes such as immersion, orientation, and audio guidance](/assets/projects/Focal-Point/interviews.png)

---

## Tools & implementation

- **Projected environment**
  - Processing 4 (Java)
  - Kinect depth camera (OpenKinect)
  - Minim (audio)
  - Single-user interaction in a shared visual space

- **VR environment**
  - Unity
  - Meta Quest 2 with hand tracking
  - Custom C# scripts recreating the focal-point logic
  - Spatial audio and abstract 360° environments

---

## Why it matters

Focal Point acts as a **bridge project** between interactive art and research:

- It demonstrates how different mediums shape perception, focus, and embodied searching.
- It informs later work on **VR instruments**, **immersive focus tools**, and exploratory XR environments.
- It provides a practical framework for comparing modalities when designing sensory-driven interaction.

---

## What’s next

Future directions include:

- Extending stages to emphasise flow over “correct answers”.
- Refining audiovisual behaviour for comfort and accessibility.
- Integrating biometric or biofeedback data (e.g. breathing or heart rate).
- Reusing concepts and code as foundations for later VR and interactive projects.
