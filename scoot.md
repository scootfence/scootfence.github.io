---
permalink: scoot/index.html
title: Scoot
layout: pages
---

## Scoot

{% for post in site.posts %}

<div class="scoot-post">
{% if post.title %}
<h3>{{post.title}}</h3>
{% endif %}

{{ post.content }}
</div>
{% endfor %}