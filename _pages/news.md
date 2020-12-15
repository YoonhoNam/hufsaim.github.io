---
layout: collection
title: "News"
permalink: /news/
collection: news
author_profile: false
---

{% for post in site.news %}
  {% unless post.hidden %}
    {% include archive-single.html %}
  {% endunless %}
{% endfor %}
