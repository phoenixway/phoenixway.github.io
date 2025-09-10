---
layout: home
---

# Applied Systems Thinking

My name is Roman Kozak, a technologist specializing in software development and automation. My work is focused on creating robust, secure, and pragmatic solutions for complex challenges. 

**[View my full Tech Stack]({{ site.baseurl }}/stack/)**.

---

## Featured Projects

<div class="project-showcase">
  <div class="project-item">
    <h3>Forward App (Android)</h3>
    <p>A native mobile application for Android, demonstrating skills in Kotlin, offline-first architecture, and goal management.</p>
    <a href="https://github.com/phoenixway/forwardapp-android" class="btn" target="_blank" rel="noopener noreferrer">View Project</a>
  </div>
  <div class="project-item">
    <h3>Bogdana Security</h3>
    <p>A multi-functional toolkit focused on enhancing system security through automation and robust tools.</p>
    <a href="https://github.com/phoenixway/bogdana-security" class="btn" target="_blank" rel="noopener noreferrer">View Project</a>
  </div>
  <div class="project-item">
    <h3>Obsidian AI Forge</h3>
    <p>A project leveraging AI to augment knowledge management workflows and automate note-taking in Obsidian.</p>
    <a href="https://github.com/phoenixway/obsidian-ai-forge" class="btn" target="_blank" rel="noopener noreferrer">View Project</a>
  </div>
</div>

**... see all my work on the [full projects page]({{ site.baseurl }}/projects/).**

## Last Articles

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span style="color: #999;">- {{ post.date | date: "%d.%m.%Y" }}</span>
    </li>
  {% endfor %}
</ul>