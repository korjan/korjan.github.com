---
layout: page
title: Ideas, Projects, Music &amp; Pictures
tagline: Home of The Gentle Fellows, 6-Pack Think Tank & Revenge of the Nerds Inc.
---
{% include JB/setup %}

Hello html parsing...

<ul class="posts">
	<li>Any posts here?</li>
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>