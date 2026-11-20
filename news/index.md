---
title: News
nav:
  order: 3
  tooltip: Latest news from the lab
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}News

What is going on in the lab? Discover it here!

{% include section.html %}

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
