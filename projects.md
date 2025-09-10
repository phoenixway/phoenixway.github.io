---
layout: home
title: "Projects"
permalink: /projects/
---

## My projects 🚀

{% for project in site.projects %}
<div class="project-card">
  <h3>
    <a href="{{ project.link }}" target="_blank" rel="noopener noreferrer">{{ project.title }}</a>
  </h3>
  
  <p><strong>Опис:</strong> {{ project.content | strip_html | truncatewords: 30 }}</p>

  <p><strong>Технології:</strong> {{ project.tags | join: ", " }}</p>
  <p><a href="{{ project.link }}" target="_blank" rel="noopener noreferrer" class="btn">Переглянути на GitHub</a></p>
</div>
{% endfor %}