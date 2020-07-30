---
layout: page
title: OpenArchive News
description:
permalink: /news/
---

  <div class="row">
	<div class="6u 12u$(medium)">
    {% for post in site.posts %}
    <div>
    <b><a href="{{ site.baseurl }}{{ post.url }}" style="color: #00B4A6">{{ post.title }}</a></b> <br><span style="font-style: italic; font-size: 14px;">{{ post.date | date_to_string }}</span>
    <p style="margin-top: 6px">{{ post.description }}</p>
    </div>
    {% endfor %}
					</div>
					<div class="6u$ 12u$(medium)">
<a class="twitter-timeline" href="https://twitter.com/open_archive?ref_src=twsrc%5Etfw">Tweets by open_archive</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


					</div>
				</div>
