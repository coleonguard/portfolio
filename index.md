---
layout: default
title: Home
---

# Welcome to My GitHub Pages Site

This is a simple website using the **Hyde theme**.

Here are some of my latest posts:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
