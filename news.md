---
layout: page
title: News
description: copy goes here.
permalink: /news/
---

<div class="row">
					<div class="6u 12u$(medium)">
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

					</div>
					<div class="6u$ 12u$(medium)">
<a class="twitter-timeline" href="https://twitter.com/open_archive?ref_src=twsrc%5Etfw">Tweets by open_archive</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 


					</div>
				</div>




