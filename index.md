---
title: "Test Blog"
---

## Here are my posts

<ul>
{% for post in site.posts %}
<li>
<a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>
