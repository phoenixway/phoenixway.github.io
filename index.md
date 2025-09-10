---
layout: home
title: "Ласкаво просимо!"
---

Привіт! 👋 Я **PhoenixWay**, IT-розробник.  

Тут ти знайдеш мої проекти, статті та контакти.  

- Досвід у: Web, Python, Git, Linux  
- Люблю: чистий код та автоматизацію  

---

## Останні статті

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color: #999;">- {{ post.date | date: "%d.%m.%Y" }}</span>
    </li>
  {% endfor %}
</ul>