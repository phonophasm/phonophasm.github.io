---
layout: default
title: Blog
permalink: /blog/
---

# Blog

{% if site.posts.size > 0 %}
  {% for post in site.posts %}
  <div class="card">
    {% if post.hero_image %}
    <a href="{{ post.url | relative_url }}" class="post-card-image-link">
      <img src="{{ post.hero_image | relative_url }}" alt="{{ post.title }} cover art" class="post-card-image" />
    </a>
    {% endif %}
    <h3 style="margin:0;"><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <small>{{ post.date | date: "%b %d, %Y" }}</small>
    {% unless post.hero_image %}
    {% if post.excerpt %}
    <p>{{ post.excerpt }}</p>
    {% endif %}
    {% endunless %}
  </div>
  {% endfor %}
{% else %}
  <p>No posts yet.</p>
{% endif %}
