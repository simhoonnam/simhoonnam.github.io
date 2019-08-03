---
layout: page
title: Tags
permalink: /tags/
image: /files/covers/bg.png
sitemap:
priority: 0.7
---

**태그는 `[ctrl + f]` 후에 영어로 검색!**  

---

## 모든 태그

{% for tag in site.tags %}
* [{{ tag.name }}]({{ site.baseurl }}/tags/{{ tag.name }})
{% endfor %}
