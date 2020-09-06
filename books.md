---
layout: page
title: "Books"
permalink: /books/
---

### What I'm Reading Right Now
- [Superintelligence: Paths, Dangers, Strategies](https://www.goodreads.com/book/show/20527133-superintelligence)
- [Nudge: Improving Decisions About Health, wealth, and Happiness](https://www.goodreads.com/book/show/3450744-nudge)


### Past Reviews
<ul>
  {% for post in site.categories.book-review %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> posted {{post.date | date: "%b %-d %Y"}}
    </li>
  {% endfor %}
</ul>
