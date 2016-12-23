---
layout: page
title: Archive
active: blog
---

{% for post in site.posts %}
<p>
	{{ post.date | date_to_string }}
	&mdash;
	<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
</p>
{% endfor %}