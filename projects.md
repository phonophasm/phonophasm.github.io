---
layout: default
title: Projects
permalink: /projects/
---

# Projects

{% assign things = site.projects | sort: 'weight' %}
{% for p in things %}
<div class="card">
  <h3 style="margin:0;"><a href="{{ p.url | relative_url }}">{{ p.title }}</a></h3>
  <p>{{ p.summary }}</p>
  {% if p.links %}
    <p>{% for l in p.links %}<a href="{{ l.url }}" target="_blank" rel="noopener">{{ l.label }}</a>{% unless forloop.last %} • {% endunless %}{% endfor %}</p>
  {% endif %}
  {% if p.tags %}
    <p>{% for t in p.tags %}<span class="tag">{{ t }}</span>{% endfor %}</p>
  {% endif %}
</div>
{% endfor %}

<p><em>Add more by creating files in <code>_projects/</code>.</em></p>
