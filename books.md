---
layout: home
title: "Books"
permalink: /books/
---



### What I'm Reading Right Now
<div class="bookshelf">
  <a href="https://www.goodreads.com/book/show/101255.On_Food_and_Cooking"> 
    <div class="book">
      <div class="side spine" style="background-color: #b81c1c">
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
  <a href="https://www.goodreads.com/book/show/30659.Meditations"> 
    <div class="book">
      <div class="side spine" style="background-color: black">
        <span class="spine-title"> Meditations</span>
        <span class="spine-author">
          MA
        </span>
      </div>
      <div class="side top"></div>
      <div
        class="side cover"
        style="background-image: url(https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1421618636l/30659.jpg)"
      ></div>
    </div>
  </a>
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

<div class="bookshelf">
  <a href="https://www.goodreads.com/book/show/101255.On_Food_and_Cooking"> 
    <div class="book">
      <div class="side spine" style="background-color: #0048ba">
        <span class="spine-title"> On Food and Cooking </span>
        <span class="spine-author">
          HG
        </span>
      </div>
      <div class="side top"></div>
      <div
        class="side cover"
        style="background-image: url(https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1556604137l/34466963._SY475_.jpg)"
      ></div>
    </div>
  </a>
  <a href="https://www.goodreads.com/book/show/316767.The_Box"> 
    <div class="book">
      <div class="side spine" style="background-color: #468499">
        <span class="spine-title"> The Box</span>
        <span class="spine-author">
          ML
        </span>
      </div>
      <div class="side top"></div>
      <div
        class="side cover"
        style="background-image: url(https://i.gr-assets.com/images/S/compressed.photo.goodreads.com/books/1442129363l/316767._SY475_.jpg)"
      ></div>
    </div>
  </a>
</div>

<br/><br/>