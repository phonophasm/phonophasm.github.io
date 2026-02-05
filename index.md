---
layout: default
title: Home
---

<img src="{{ '/assets/images/pete-portrait.PNG' | relative_url }}" alt="Portrait of Pete" class="circle-image profile-image" />

Hi — I’m Pete (Phonophasm). I make music, VR instruments, and new-media experiments.

<p>
My work explores immersive sound and virtual environments as tools for attention, memory, and shared experience — often through playful, embodied interaction.
</p>

<p>
Outside of my creative work, I enjoy travelling, swimming, cycling, yoga, and keeping a healthy balance between making and resting.
</p>

## Latest posts
{% assign recent = site.posts | slice: 0, 3 %}
{% if recent and recent.size > 0 %}
  {% for post in recent %}
  <div class="card">
    <h3 style="margin:0;"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <small>{{ post.date | date: "%b %d, %Y" }}</small>
    {% if post.excerpt %}
    <p>{{ post.excerpt }}</p>
    {% endif %}
  </div>
  {% endfor %}
{% else %}
  <p><em>No posts yet — write your first one in <code>_posts/</code>.</em></p>
{% endif %}

## Featured projects

<div class="card">
  <a href="https://phonophasm.github.io/projects/phonosphere/" style="text-decoration:none;">
    <img src="{{ '/assets/images/phonosphere.png' | relative_url }}" alt="Screenshot of the PHONOSPHERE VR instrument interface" class="circle-image project-image" />
  </a>
  <h3 class="project-title">
    <a href="https://phonophasm.github.io/projects/phonosphere/">PHONOSPHERE VR instrument</a>
  </h3>
  <p>
    A VR instrument for ambient and experimental performance on Quest headsets. Spatial “sound objects” are triggered and shaped through hand tracking, encouraging exploratory play and embodied musical gesture.
  </p>
  <p><a href="https://phonophasm.github.io/projects/vr-instrument/">View project →</a></p>
</div>

<div class="card">
  <a href="https://phonophasm.github.io/projects/neo-sense-vr/" style="text-decoration:none;">
    <img src="{{ '/assets/images/neo-sense.png' | relative_url }}" alt="Neo-Sense VR concept art" class="circle-image project-image" />
  </a>
  <h3 class="project-title">
    <a href="https://phonophasm.github.io/projects/neo-sense-vr/">Neo-Sense VR</a>
  </h3>
  <p>
    A research project exploring sensory manipulation and “sense swapping” in VR. Built in Unity, it investigates how remapped cues influence attention, search behaviour, immersion, and comfort.
  </p>
  <p><a href="https://phonophasm.github.io/projects/neo-sense-vr/">View project →</a></p>
</div>

<div class="card">
  <a href="https://phonophasm.github.io/projects/matsu-vr/" style="text-decoration:none;">
    <img src="{{ '/assets/images/matsu.png' | relative_url }}" alt="VR installation view from the Matsu project" class="circle-image project-image" />
  </a>
  <h3 class="project-title">
    <a href="https://phonophasm.github.io/projects/matsu-vr/">Matsu VR</a>
  </h3>
  <p>
    A narrative VR experience inspired by Taiwan’s Matsu Islands. Documentary-style vistas, spatial sound, and gentle interaction explore presence, memory, and how immersive media can frame geopolitical tension through lived experience.
  </p>
  <p><a href="https://phonophasm.github.io/projects/matsu-vr/">View project →</a></p>
</div>

<div class="card">
  <a href="https://phonophasm.github.io/projects/focal-point-vr/" style="text-decoration:none;">
    <img src="{{ '/assets/images/focal-point.png' | relative_url }}" alt="Focal Point project artwork featuring concentric circles" class="circle-image project-image" />
  </a>
  <h3 class="project-title">
    <a href="https://phonophasm.github.io/projects/focal-point-vr/">Focal Point</a>
  </h3>
  <p>
    An audio-visual work about focus, distraction, and perception — using layered ambient textures and minimal visuals. A bridge between improvised music and visual experimentation, and a precursor to later interactive/VR pieces.
  </p>
  <p><a href="https://phonophasm.github.io/projects/focal-point-vr/">View project →</a></p>
</div>
