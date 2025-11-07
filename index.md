---
layout: default
title: Home
---

# {{ site.title }}

Hi — I’m Pete. I make music, VR instruments, and new‑media experiments.

<nav class="site-nav">
  <a href="{{ '/blog/' | relative_url }}">Blog</a>
  <a href="{{ '/projects/' | relative_url }}">Projects</a>
  <a href="{{ '/about/' | relative_url }}">About</a>
</nav>

---

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
    {% if post.tags %}
      <p>{% for t in post.tags %}<span class="tag">{{ t }}</span>{% endfor %}</p>
    {% endif %}
  </div>
  {% endfor %}
{% else %}
  <p><em>No posts yet — write your first one in <code>_posts/</code>.</em></p>
{% endif %}

## Featured projects

### PhonoSPHERE VR Instrument
A VR instrument for ambient and experimental performance using Quest headsets. Spatial objects trigger and modulate sound through hand tracking, creating an embodied, exploratory interface and a testbed for future bio/neurofeedback interaction.

### NeoSense VR
A VR research project exploring sensory manipulation and “sense swapping” in virtual environments. Built in Unity, it investigates how remapped sensory cues affect search behaviour, attention, immersion, and comfort.

### Matsu VR
A narrative VR experience based on Taiwan’s Matsu Islands. Combines documentary-style vistas, spatial sound, and interactive cues to explore presence, memory, and how immersive media can frame geopolitical tension from a human perspective.

### Focal Point
An audio-visual project about focus, distraction, and perception, using layered ambient textures and minimal visuals. Bridges improvised music with visual experimentation and informs later interactive and VR work.
