---
layout: home
title: "Archives"
permalink: /archives/
---

"The archives must be incomplete..." - Obi-wan


Here is where I store all my past posts.

### Reading List 2020
<ul>
  {% for post in site.categories.book-review %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> posted {{post.date | date: "%b %-d %Y"}}

    </li>
  {% endfor %}
</ul>


### All Past Blog Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> posted {{post.date | date: "%b %-d %Y"}}
    </li>
  {% endfor %}
</ul>
