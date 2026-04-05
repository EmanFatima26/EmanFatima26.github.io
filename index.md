---
layout: default
title: Home
---

# Welcome to my Blog!
 My name is Eman Ftima and I am a Computer Engineering student sharing my journey.

### Recent Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>

[Create a New Post](https://github.com){: .btn}
