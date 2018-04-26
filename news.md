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


Twitter feed to go here <https://help.twitter.com/en/using-twitter/embed-twitter-feed>