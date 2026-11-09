---
title: "PHONOSPHERE — spatial VR instrument"
layout: default
tags: [VR, Unity, Music, Instrument, Quest 3, Spatial Audio, OSC, Reaper]
---

# PHONOSPHERE — spatial VR instrument

*An evolving instrument for making music through touch, movement, and sound arranged in space.*

PHONOSPHERE began as a hand-played sampler for Meta Quest 3. I am developing it in two connected directions: a self-contained VR instrument and an experimental controller for spatial audio in Reaper. Both explore how a musician can place, trigger, and move sounds through physical gesture.
{: .tldr-highlight }

**Status:** Active development. The Quest-to-Reaper connection is working experimentally; the broader hybrid instrument and performance workflow are still being refined.

**Try the earlier demo:** [PHONOSPHERE on SideQuest](https://sidequestvr.com/app/45447). It represents an earlier stage of the project, rather than the current Reaper-connected setup.

<figure>
  <img src="{{ '/assets/projects/phonosphere/title list image.png' | relative_url }}" alt="PHONOSPHERE title image showing two hands reaching toward a glowing sphere in a forest" />
  <figcaption>PHONOSPHERE's hand-based approach to playing sound in VR.</figcaption>
</figure>

## Playing and composing in VR

In the Quest, sound objects are arranged around the player and activated through hand movement. Recent development has explored sample pads, internal and external samples, and a looper for building layers over time. The looper and sample-loading workflow remain in development; the aim is to make arranging a sound world feel as immediate as playing an instrument.

<figure>
  <img src="{{ '/assets/posts/2026-03/01 layout.png' | relative_url }}" alt="Unity development view of PHONOSPHERE with coloured sound spheres and controls arranged around the player" />
  <figcaption>A development view of the spatial layout and controls. Read the <a href="{% post_url 2026-03-15-PHONOSPHERE-Development-Update %}">March 2026 update</a> for the sampler and looper experiments.</figcaption>
</figure>

The instrument has also become a way to write music. I composed [XPLONATI]({% post_url 2026-09-16-XPLONATI %}) using PHONOSPHERE, then developed the album further in Reaper.

## Connecting VR to spatial audio

The current experimental setup sends interaction and position data from PHONOSPHERE on Quest 3 over OSC to a Python desktop bridge. The bridge passes control data to Reaper, where tracks and ambisonic tools can respond to movement in VR. I have tested hand movement as a way to change the spatial position of drum and vocal material.

<figure>
  <img src="{{ '/assets/posts/2026-06/flow connection.png' | relative_url }}" alt="Signal flow from PHONOSPHERE on Quest 3 through OSC and a Python bridge to Reaper and spatial audio output" />
  <figcaption>The experimental Quest-to-Reaper signal path. <a href="{{ '/assets/posts/2026-06/flow connection.png' | relative_url }}">Open the diagram at full size</a>, or read the <a href="{% post_url 2026-06-12-PHONOSPHERE-Development-Update %}">June 2026 development update</a> for more detail.</figcaption>
</figure>

## Testing beyond headphones

In October 2026, I began testing PHONOSPHERE with the surround speaker system at the Sonic Arts Research Centre in Belfast. These early sessions revealed setup issues that still need work, while offering an encouraging first test of how VR movement and sound in a room might connect. I have also tried the instrument with QUBe, an improvised experimental music group.

<figure>
  <img src="{{ '/assets/images/PHONOSPHERE in surround 1 OCT 2026.PNG' | relative_url }}" alt="A performer wearing a VR headset and raising both hands in SARC's surround studio, with speakers around the room" />
  <figcaption>First PHONOSPHERE tests with SARC's ambisonic speaker system. Read the <a href="{% post_url 2026-10-26-Starting-Again-in-Belfast %}">October 2026 update</a>.</figcaption>
</figure>

## Current priorities

- Improve the reliability of OSC communication and the Quest-to-Reaper workflow.
- Refine hand-controlled spatial movement and the mapping between VR objects and audio tracks.
- Continue developing looping, sample loading, and ways to save and revisit sound-world layouts.
- Explore how the standalone Quest instrument and the Reaper-connected setup can share a clear, playable interface.

PHONOSPHERE is built by **Peter Harrison**. For help with the earlier demo, see the [PHONOSPHERE support page]({{ '/support/' | relative_url }}). For a demonstration or collaboration, use the contact links on this site.
