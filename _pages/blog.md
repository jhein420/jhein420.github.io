---
layout: default
title: Blog
permalink: /blog
---

## Posts

Below are posts detailing the projects I am currently working on or have
completed or other topics or things in the tech space that have caught my attention.

<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}" class="post-preview">{{ post.title }}</a></li>
  {% endfor %}
</ul>
