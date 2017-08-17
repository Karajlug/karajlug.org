---
layout: default
---

# $ cat /proc/about
{:id="about"}

**TODO** description about dublug

# $ find /home/KarajLug -iname "contact"
{:id="contact"}
Join us via:
* [#5hit](http://webchat.freenode.net/?channels=5hit&uio=d4) channel on irc.freenode.net
  (click on the link or use IRC client such as hexchat).

# $ ps -aux|grep news
{:id="posts"}

<ul>
{% for post in site.posts %}
<li><a href="{{ post.url }}" title="{{ post.description }}">{{ post.title }}</a></li>
{% endfor %}
</ul>
