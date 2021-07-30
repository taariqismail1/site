---
layout: page
title: Test
---

Test

{% assign posts = site.posts | where:"type", "arabic" %}

<ul>
{% for post in posts %}
<li>
<a href="{{ site.url }}{{site.baseurl}}{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
<ul>
