---
layout: newhome
title: a.warm.place
subtitle: [mind.heart.life]
---

{% for post in site.posts %}
<li>
  <a href="{{post.url}}">{{post.title}}</a>
</li>
{$ endfor %}
