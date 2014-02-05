---
layout: default
title: Blog Posts
date: 2014-02-05 23:58:00
---

# The blog

<ul class="posts-list">
	{% for post in site.posts %}
	<li>
		<a href="{{post.url}}">{{post.title}}
	</li>
	{% endfor %}
</ul>