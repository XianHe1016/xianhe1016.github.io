---
layout: default
title: Home
---

# {{ site.title }}

{{ site.description }}

📧 Contact: [{{ site.email }}](mailto:{{ site.email | replace: "&#64;", "@" }})

---

## Research Interests
<ul>
  {% for interest in site.research_interests %}
    <li>{{ interest }}</li>
  {% endfor %}
</ul>

<a href="https://github.com/你的用户名" class="btn">View My GitHub Profile</a>
