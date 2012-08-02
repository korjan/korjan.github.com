---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

Hello html parsing...

<ul class="posts">
	<li>Any posts here?</li>
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>