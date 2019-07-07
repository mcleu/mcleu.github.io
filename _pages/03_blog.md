---
layout: page
title: blog
permalink: /blog/
---

This is the blog page.

{% for post in site.posts %}
{{post.title}}
{% endfor %}