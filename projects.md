---
layout: home
title: "Проекти"
permalink: /projects/
---

## Мої проекти 🚀

{% for project in site.projects %}
### [{{ project.title }}]({{ project.url }})

**Опис:** {{ project.description | markdownify }}

**Технології:** {{ project.tags | join: ", " }}

[Переглянути на GitHub]({{ project.link }})
{% endfor %}
