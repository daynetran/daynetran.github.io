---
layout: home
title: The Slash S
permalink: /slashs/
---
<style>
    li {text-align: left;}
    a {color: greenyellow}
</style>


# **Past /S Articles**

  <ul>
  {% for post in site.categories.SlashS %}
    <li>
      <h3> <a href="{{ post.url }}">{{ post.title }}</a> posted {{post.date | date: "%b %-d %Y"}} </h3>  {{post.excerpt}} 
    </li>
  {% endfor %}
  </ul>
  