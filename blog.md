---
layout: posts
title:  "Blog"
date:  2019-04-21
categories: pages
#tags: featured
#image: /assets/article_images/2019-04-21-streaks-or-luck/cleveland_streak.jpg
#permalink: /:categories/:title
---
{% for post in site.posts %}
  <li><a href="{{ post.url }}">{{post.title}}</a></li>
{% endfor %}
