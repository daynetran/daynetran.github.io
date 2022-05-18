---
layout: home
title: "Books"
permalink: /books/
---



### What I'm Reading Right Now
- [Superintelligence: Paths, Dangers, Strategies](https://www.goodreads.com/book/show/20527133-superintelligence)
- [Nudge: Improving Decisions About Health, wealth, and Happiness](https://www.goodreads.com/book/show/3450744-nudge)


<div class="bookshelf">
  <a href="https://www.goodreads.com/book/show/101255.On_Food_and_Cooking"> 
    <div class="book">
      <div class="side spine" style="background-color: red">
        <span class="spine-title"> On Food and Cooking </span>
        <span class="spine-author">
          HG
        </span>
      </div>
      <div class="side top"></div>
      <div
        class="side cover"
        style="background-image: url(https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1347221060l/101255.jpg)"
      ></div>
    </div>
  </a>
  <a href="https://www.gopl.io/"> 
    <div class="book">
      <div class="side spine" style="background-color: lightblue">
        <span class="spine-title"> The Go Programming Language </span>
        <span class="spine-author">
          AD & BK
        </span>
      </div>
      <div class="side top"></div>
      <div
        class="side cover"
        style="background-image: url(https://www.gopl.io/cover.png)"
      ></div>
    </div>
  </a>
      <div class="book">
      <div class="side spine">
        <span class="spine-title"> The Anthropocene Reviewed </span>
        <span class="spine-author">
          JG
        </span>
      </div>
      <div class="side top"></div>
      <div
        class="side cover"
        style="background-image: url(https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1616514130l/55145261.jpg)"
      ></div>
    </div>
</div>

<br/><br/>

### Past Reviews
<ul>
  {% for post in site.categories.book-review %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> posted {{post.date | date: "%b %-d %Y"}}
    </li>
  {% endfor %}
</ul>
