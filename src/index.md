---
title: Hello World
layout: "base.njk"
---

Hello from Eleventy!

{% for post in collections.posts %}
- [{{ post.data.title }}]({{ post.url }})
{% endfor %}
