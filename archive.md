---
layout: page
title: Archive
permalink: /archive/
---

This page will contain a link to all previous posts made on this site.

{% for post in site.posts %}
  * {{ post.date | date_to_string }} [ {{ post.title }} ]({{ post.url | prepend: site.baseurl }})
{% endfor %}