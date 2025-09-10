---
layout: home
---

# Building Bridges Between Code and Complex Systems

My name is Roman Kozak, a technologist specializing in software development and systems thinking. My work focuses on creating robust, secure, and intelligent solutions.

Beyond traditional software, I apply my skills to a broader mission: structuring knowledge and solving problems in complex domains, from creative explorations to health informatics.

This is my digital space where I share my professional work and insights.

---

### Key Areas

* **Software & Security:** Building secure applications and automation tools.
* **System Analysis:** Applying structured thinking to complex challenges.
* **Knowledge Structuring:** Organizing information for practical application.

---

### Explore My Work

* **[Technical Projects]({{ site.baseurl }}/projects/)**: A showcase of my software development and security work.
* **[Articles]({{ site.baseurl }}/articles/)**: My thoughts on technology, automation, and system design.
* **[Explorations Site]({{ site.baseurl }}/personal/)**: A lab for my non-technical research and creative ventures.
* **[Animal Care Initiative]({{ site.baseurl }}/animal-care/)**: A knowledge base for zoo volunteers and pet owners.

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