---
title: COMP282
layout: article
aside:
 toc: true
sidebar:
 nav: comp282
---
{% for post in site.posts %}
{% if post.tags contains "COMP282" %}
# [{{post.title}}]({{site.baseurl}}{{post.url}})
{::nomarkdown}
{{post.content}}
{:/nomarkdown}
{% endif %}
{% endfor %}