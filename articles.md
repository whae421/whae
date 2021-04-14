---
layout: default
title: Articles
cover: false
about: 'about.html'
---

<main>
  <ul>
    {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
  </ul>
</main>