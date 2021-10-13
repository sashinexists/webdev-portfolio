---
title: about
published_date: "2021-10-12 23:29:11 +0000"
layout: default.liquid
is_draft: false
---
{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
