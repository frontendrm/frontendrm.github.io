---
layout: page
title: Themen
permalink: themen.html
---

{% assign postsByYear =
    site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in postsByYear %}
## {{ year.name }}
{% for post in year.items %} - [{{post.title}}]({{post.url}})
{% endfor %}
{% endfor %}

