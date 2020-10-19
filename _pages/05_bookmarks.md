---
layout: default
title: Bookmarks
permalink: /bookmarks/
---

**Testing Conferences:** [testingconferences.org](https://testingconferences.org/)  

{% for bookmark in site.data.bookmarks %}
* [{{ bookmark.name }}]({{ bookmark.url }})
{% endfor %}
