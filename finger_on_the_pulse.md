---
layout: home
title: Finger on the Pulse
permalink: /finger_on_the_pulse/
---
<style>
    li {text-align: left;}
    a {color: greenyellow}
</style>


# **Past /S Articles**

  <ul>
  {% for post in site.categories.FingerOnThePulse %}
    <li>
      <h3> <a href="{{ post.url }}">{{ post.title }}</a> posted {{post.date | date: "%b %-d %Y"}} </h3>  {{post.excerpt}} 
    </li>
  {% endfor %}
  </ul>
  