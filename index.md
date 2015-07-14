---
layout: page
title: Index
permalink: /index/
---

<ul class="post-list-index">
{% for post in site.posts %}
	<li class="post-single"><a href="{{ post.url | prepend: site.baseurl }}"><span class="post-single-meta">{{ post.date | date_to_string }}</span><span class="post-single-title">{{ post.title }}</span></a></li>
{% endfor %}
</ul>