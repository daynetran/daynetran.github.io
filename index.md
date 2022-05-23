---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
title: About
link: /about/
---

<style>
body {margin:25px;}

div.polaroid {
  width: 80%;
  background-color: black;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  margin-bottom: 25px;
}

div.container {
  text-align: center;
  padding: 10px 20px;
}
</style>

Heyooo! I'm Dayne, and thank you for coming here, to my little corner of the world wide web. I hail from SoCal, but I've been calling NorCal home for the past 4 years. I'm about to be a senior at UC Berkeley, and I'm studying both economics and computer science (I know, I sold out, *sheepish shrug*).

When I'm not finishing my coding projects at 2am at Soda Hall or dozing off in my behavioral economics lectures, I'm doing a lot of other stuff! During the school year, I work 2 jobs: equipment manager for the [Cal Football Team](https://www.instagram.com/cal_football/) and peer advisor for the [Berkeley econ department](https://www.instagram.com/cal_econadvising/). In whatever free time I have left, I volunteer for [Cal Habitat for Humanity](https://www.calhabitat.org/) and play *way too much* [basketball](https://streamable.com/o29pcc). This summer, I'm working full-time for [Humanitas.ai](https://humanitas.ai/) as a software engineering intern.

Alright, I'm done with the autobiographical schpiel. This site serves two purposes. First, I hope that this body of work serves a time capsule where 20 years from now, I can look back at my work here proudly. Second, I want to record my thoughts on everything that goes on in my life. I want to write satirical commentary, fictional prose, ruminations on books I'm reading, and so much more.

Lastly, I have a Substack page, too. If you prefer reading on the Substack platform, you can find all my posts there, and if you *really really* love my content, you can tip me through that too ;).

<center>
<div class="polaroid">
    <img src="/assets/images/habitatpicture.jpg">
    <div class="container">
    <p>March 2022: Kailey, Marco, and I enjoying some clean-ass water</p>
    </div>
</div>
</center>

## **Blog Posts**
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> posted {{post.date | date: "%b %-d %Y"}}
    </li>
  {% endfor %}
</ul>