---
layout: default
title: Blog
permalink: /blog/
---

# Blog

{% if site.posts.size > 0 %}
  {% for post in site.posts %}
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
  <p>No posts yet.</p>
{% endif %}
