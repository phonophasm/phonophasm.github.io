---
layout: default
title: Home
---

# {{ site.title }}

Hi — I’m **Your Name**. I make music, VR instruments, and new‑media experiments.

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
{% assign featured = site.projects | where: "featured", true | sort: 'weight' %}
{% if featured and featured.size > 0 %}
  {% for p in featured %}
  <div class="card">
    <h3 style="margin:0;"><a href="{{ p.url | relative_url }}">{{ p.title }}</a></h3>
    <p>{{ p.summary }}</p>
    {% if p.tags %}
      <p>{% for t in p.tags %}<span class="tag">{{ t }}</span>{% endfor %}</p>
    {% endif %}
  </div>
  {% endfor %}
{% else %}
  <p><em>Mark any project with <code>featured: true</code> to show it here.</em></p>
{% endif %}
