---
layout: archive
permalink: /blogs/
title: "Blog Posts"
---

<div class="tiles">
{% for post in site.posts %}
	{% if post.category == "blog" %}
	{% include post-grid.html %}
	{% endif %}
{% endfor %}
</div><!-- /.tiles -->