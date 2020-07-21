---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


<ul>
  {% for post in site.posts %}
      <header>
        <a href="{{ post.url }}">{{ post.title }}</a> posted {{post.date | date: "%b %-d %Y"}}
      <header>
      {{post.content | truncatewords:50}}

  {% endfor %}
