---
layout: page
title: Archive
active: blog
tags: [b3, posts, blog, archive]
description: The archive of all B3's blog posts.
---

{% for post in site.posts %}
<p>
	{{ post.date | date_to_string }}
	&mdash;
	<a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
</p>
{% endfor %}