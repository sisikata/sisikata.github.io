---
layout: home
author_profile: true
show_title: false
---

# Selamat datang di **Sisi Kata**  
Tempat di mana kata-kata menjadi makna.

---

## Recent Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a><br>
      <small>{{ post.date | date: "%d %B %Y" }}</small><br>
      <p>{{ post.excerpt | strip_html | truncatewords: 20 }}</p>
    </li>
  {% endfor %}
</ul>
