---
layout: default
title: "PHONOSPHERE Development Update – Quest 3, OSC, Reaper, and Ambisonic Control"
date: 2026-06-12
categories: [PHONOSPHERE, VR, Spatial Audio, Development]
tags: [Quest 3, OSC, Reaper, ambisonics, Python, VR music, spatial audio]
---

The latest stage of PHONOSPHERE development has been focused on connecting the VR instrument to a more powerful spatial audio workflow.

Until now, much of the project has been about building the instrument inside Unity and the Quest 3: arranging sound spheres, triggering samples, testing layouts, experimenting with interaction, and developing PHONOSPHERE as a tool for writing and performing music.

The newest development connects that VR interaction to Reaper through OSC and a Python desktop app.

This is a big step because it allows PHONOSPHERE to move beyond a self-contained VR prototype and become part of a professional spatial audio system.

![PHONOSPHERE flow connection from Unity to headphones]({{ '/assets/posts/2026-06/flow connection.png' | relative_url }})

## Quest 3 to Python to Reaper

The current setup allows the Quest 3 to send OSC data from Unity to a Python desktop app.

The Python app acts as a bridge between the headset and Reaper. It receives movement and interaction data from PHONOSPHERE, then communicates that data to the audio system.

This means that actions inside VR can now control audio behaviour inside Reaper.

The basic chain is:

**Quest 3 / Unity**  
↓ OSC  
↓ Python desktop bridge  
↓ Reaper  
↓ Ambisonic spatial audio processing

This opens up a much richer performance setup. Instead of only playing audio inside the headset, PHONOSPHERE can now control external tracks, effects, and spatial positions in a DAW.

## Ambisonic Communication with Reaper

One of the most important additions is ambisonic communication with Reaper.

In Reaper, I have been working with ambisonic tools to spatialise sound more seriously. PHONOSPHERE can now send positional data from VR into Reaper, allowing sound movement in the virtual space to be reflected in the ambisonic mix.

This brings the project closer to a complete spatial audio instrument that can be used for composition, recording, and live performance.

The long-term aim is not only to place sounds around a player in VR, but to create sound worlds that can also be rendered, performed, documented, and potentially translated into immersive speaker environments.

It also creates a path toward using PHONOSPHERE with immersive speaker systems as well as headphones.

![PHONOSPHERE ambisonic spatial audio setup]({{ '/assets/posts/2026-06/ambisonics.png' | relative_url }})

## Hand Movement and Spatial Performance

Another recent experiment uses hand movement to control the spatial position of specific sounds.

At the moment, I have been testing this with drum and vocal material.

This means that the performer’s hand movement can affect where drums or vocals sit in space. Instead of treating spatial audio as something adjusted with knobs or automation lanes, the body becomes the controller.

This is an important design direction for PHONOSPHERE.

It makes spatial mixing feel more like performance.

Movement becomes part of the musical technique, giving the performer a direct way to shape distance, direction, motion, and presence in the mix.

A vocal sound can be brought closer.

A drum sound can move around the listener.

A texture can be pushed away, circled, hidden, or made present.

Spatial audio becomes something felt through action, not only edited visually on a screen.

## Why Use Reaper?

Reaper is useful because it gives PHONOSPHERE access to a much deeper audio environment.

Inside Reaper, I can work with:

- Ambisonic routing
- Spatial audio plugins
- Individual instrument tracks
- Sample playback
- MIDI control
- Automation
- Effect processing
- Live performance routing
- Recording and rendering

![PHONOSPHERE energy visualiser in Reaper]({{ '/assets/posts/2026-06/energy visualiser.png' | relative_url }})

This gives PHONOSPHERE two possible modes of operation.

First, it can be a standalone VR sampler and sound-world tool.

Second, it can become a spatial controller for a larger audio system.

That hybrid direction feels important. A standalone headset version keeps the instrument immediate and portable, while the Reaper-connected version provides more control for recording, spatial audio production, and live performance.

## The Python Desktop App

The Python desktop app is becoming a key part of the system.

It is not just a technical bridge. It is also a control layer that can help manage communication between VR and the DAW.

This opens up future possibilities such as:

- Choosing which Reaper tracks receive data
- Mapping VR objects to audio tracks
- Controlling ambisonic position
- Triggering samples or MIDI notes
- Switching between songs or sample sets
- Saving project layouts
- Loading external configuration files
- Debugging communication between headset and computer

The current version is still experimental, but it is already making the system feel more flexible and expandable.

![PHONOSPHERE Python desktop bridge app]({{ '/assets/posts/2026-06/bridge app.png' | relative_url }})

## Why This Matters for PHONOSPHERE

This update changes the scale of the project.

PHONOSPHERE is no longer only a VR scene with sound objects.

It is becoming a bridge between immersive interaction and spatial audio production.

The aim is to make immersive interaction a practical part of writing, arranging, and performing music.

OSC, Python, Reaper, and ambisonics are not the final goal.

They are the infrastructure that allows musicians to create and perform richer spatial compositions.

## Current Direction

The next development phase is about bringing the standalone and external-audio versions closer together.

I am currently thinking about a hybrid PHONOSPHERE scene where the same spatial layout can either:

- Play samples directly inside the headset
- Send OSC/MIDI data to Reaper
- Or potentially switch between both modes

This would make the system more adaptable.

A standalone version could be simple and self-contained.

A performance version could connect to Reaper and use full spatial audio processing.

Both could share the same basic PHONOSPHERE logic: sounds arranged in space, controlled through movement, and saved as editable sound-world layouts.

## What Comes Next

The main priorities now are:

- Improving the hybrid VR/Reaper workflow
- Making OSC communication more reliable
- Refining hand-controlled spatial movement
- Developing clearer track and sample mapping
- Improving project saving and loading
- Keeping the system direct and understandable while performing
- Deciding which features to include in the standalone version and which require the Reaper-connected version

PHONOSPHERE is becoming more technically complex, but the core idea is still simple:

**Sound can be placed.**

**Sound can be moved.**

**Sound can be held, shaped, layered, and recorded.**

The next challenge is to make that experience reliable enough for performance, flexible enough for composition, and direct enough to feel like an instrument.
