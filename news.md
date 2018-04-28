---
layout: page
title: News
permalink: /news/
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>


<a class="twitter-timeline" href="https://twitter.com/open_archive?ref_src=twsrc%5Etfw">Tweets by open_archive</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 
