---
layout: article
permalink: /papers/
title: Research Papers
image: 
  feature: banner.jpg
share: false
modified: 2013-09-13
---

<ol class="post-list">
{% for post in site.posts %} 
 {% if post.category == "papers" %}
  <li><a href="{{ post.download }}"><b>{{ post.title }} </b><br />
  {{post.author}} <br />
  <em>{{post.conference}} </em> <br />
  <strong>{{post.annotation}} </strong>
  </a></li>
 {% endif %}
{% endfor %}
</ol>