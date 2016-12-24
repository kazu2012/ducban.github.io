---
layout: page
title: Archive
active: blog
tags: [b3, posts, blog, archive]
description: This is where you can find all of the blog posts of B3.
---

{% for post in site.posts %}
<p>
	{{ post.date | date_to_string }}
	&mdash;
	<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
</p>
{% endfor %}