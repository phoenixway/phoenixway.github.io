---
layout: home
---

# Applied Systems Thinking

My name is Roman Kozak, a technologist specializing in software development and automation. My work is focused on creating robust, secure, and pragmatic solutions for complex challenges.

This is my digital space where I share my professional work and insights. **[View my full Tech Stack]({{ site.baseurl }}/stack/)**.

---

### Explore My Work

* **[Technical Projects]({{ site.baseurl }}/projects/)**: A showcase of my software development and security work.
* **[Explorations Site](https://phoenixway.github.io/personal/)**: A lab for my non-technical research and creative ventures.
* **[Animal Care Initiative](https://phoenixway.github.io/animal-care/)**: A knowledge base for zoo volunteers and pet owners.

---

## Last Articles

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color: #999;">- {{ post.date | date: "%d.%m.%Y" }}</span>
    </li>
  {% endfor %}
</ul>