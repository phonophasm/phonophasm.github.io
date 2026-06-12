---
layout: default
title: "PHONOSPHERE Development Update – Looping, Sampling, and Building a More Flexible Instrument"
date: 2026-03-15
categories: [PHONOSPHERE, VR, Music, Development]
tags: [VR music, spatial audio, sampler, looper, Quest 3, Unity]
---

Since the last PHONOSPHERE update, I have been working on turning the project from a spatial sound demo into a more flexible instrument.

The earlier version focused on arranging sounds around the player in a 360-degree sphere. That was an important step because it made the core idea clearer:

**PHONOSPHERE is not just about triggering sounds.**

**It is about building a sound world around yourself.**

Over the past few months, I have been adding tools that make that world more playable, more flexible, and more useful for writing and performing music.

<div class="post-image-placeholder" role="img" aria-label="Placeholder for a PHONOSPHERE development overview image">
  <span>Image placeholder</span>
  PHONOSPHERE development overview
</div>

## Looper Development

One of the main additions has been the beginning of a looper system.

The goal is to let users capture musical actions and build layers inside the space, rather than only triggering one sound at a time. This moves PHONOSPHERE closer to a live instrument where a player can gradually construct an atmosphere, rhythm, or sonic environment through repeated interaction.

The looper is still developing, but it is already helping me think about PHONOSPHERE in a different way. Instead of a fixed set of sounds, it becomes a place where gestures, timing, and spatial decisions can accumulate.

Looping makes it possible to build a piece gradually through performance. Rhythms, textures, and melodic ideas can accumulate through repeated gestures without requiring a traditional music software timeline.

<div class="post-image-placeholder" role="img" aria-label="Placeholder for an image of the looper system">
  <span>Image placeholder</span>
  Looper system in development
</div>

## Sample Pad Experiments

I have also been working on sample pad functionality.

This gives PHONOSPHERE a more immediate musical mode, where sounds can be triggered quickly and rhythmically. It is useful for drums, vocal fragments, short textures, environmental sounds, and one-shot samples.

The sample pad idea supports two different ways of playing the instrument:

- PHONOSPHERE as an instrument for live performance
- PHONOSPHERE as a tool for composing and arranging sound in space

For performance, sample pads make the system feel responsive and playable.

For composition, they provide a quick way to test sounds, choose material, and begin arranging it without needing to interrupt the VR workflow.

<div class="post-image-placeholder" role="img" aria-label="Placeholder for an image of the sample pad interface">
  <span>Image placeholder</span>
  Sample pad interface
</div>

## Internal and External Sample Loading

Another important step has been improving how samples are loaded.

I have been experimenting with both internal and external sample sets. Internal samples are useful for demos, testing, and giving users an immediate starting point. External sample loading is important for the long-term goal of PHONOSPHERE because musicians need to be able to bring their own sounds into the instrument.

This could include:

- Voice recordings
- Field recordings
- Musical loops
- Drum sounds
- Short spoken phrases
- Environmental textures
- Abstract sounds
- Samples generated or processed outside the headset

This matters because PHONOSPHERE should not only be a system where users play my sounds.

It should become a space where people can arrange their own sonic material.

<div class="post-image-placeholder" role="img" aria-label="Placeholder for an image showing internal and external sample loading">
  <span>Image placeholder</span>
  Internal and external sample loading
</div>

## General Setup Improvements

A lot of development has also been focused on the less visible parts of the system.

These include:

- Cleaner scene organisation
- More reliable interaction logic
- Better sample organisation
- Clearer separation between demo sounds and user-loaded sounds
- More stable triggering behaviour
- Improved layout design for composition and live performance

These details are not always exciting to show, but they are necessary if PHONOSPHERE is going to become a reliable musical instrument rather than only a prototype.

I am also thinking more carefully about how users might save and reload their own projects in the future. A key direction is to allow sound worlds to be stored externally, possibly as JSON files, so that layouts, samples, and spatial arrangements can be edited, preserved, and revisited.

## Why This Matters

The main question I keep returning to is:

**How can a VR music system make writing, arranging, and performing spatial music feel direct and expressive?**

The technical features are not separate from that question.

A looper changes how people layer time.

A sample pad changes how quickly people can test and perform sounds.

External sample loading allows musicians to shape the instrument around their own sound libraries.

Saving and reloading projects allows compositions and performance setups to be developed over time.

These features are slowly moving PHONOSPHERE away from being a one-off demo and toward becoming a flexible environment for composition, sound design, experimentation, and live performance.

## What Comes Next

The next major development direction is deeper communication between the Quest 3 headset and external audio software.

I want PHONOSPHERE to work in two ways:

1. As a standalone VR instrument inside the headset
2. As a spatial controller for external audio systems such as Reaper

This would allow a self-contained version to run directly inside VR, while a DAW-connected version could provide ambisonic mixing, deeper spatial audio processing, recording, and live performance control.

<div class="post-image-placeholder" role="img" aria-label="Placeholder for a diagram showing the Quest 3 and external audio software connection">
  <span>Image placeholder</span>
  Quest 3 and external audio software connection
</div>

PHONOSPHERE is still evolving, but the shape of the project is becoming clearer.

It is becoming a spatial instrument.

It is becoming a sampler.

It is becoming a performance system.

And most importantly, it is becoming a place where sound can be arranged as a world.
