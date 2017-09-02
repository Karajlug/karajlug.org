---
layout: default
---

<ul class="list-post">
{% for post in site.posts %}
<li class="post">
<a href="{{ post.url }}" title="{{ post.description }}">{{ post.title }}</a>
<p>{{ post.description }}</p>
</li>
{% endfor %}
</ul>
