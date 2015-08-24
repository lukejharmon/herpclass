---
layout: default
title: Lecture notes
---

{% for post in site.categories.notes %}
- [{{post.title}}]({{site.baseurl}}{{post.url}})
{% endfor %}
