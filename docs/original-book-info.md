---
layout: default
---

## 원서 정보

> {{ site.original.description.long }}

* 도서명: [{{ site.original.title.main }}]()
* 저자: {% for author in site.data.authors-original %}[{{ author.name }}]({{ author.profile }}){% unless forloop.last%}, {% endunless %}{% endfor %}
* 출판사: [{{ site.original.publisher.name }}]({{ site.original.publisher.url }})

{% if site.original.cover.url %}
<img class="cover" src="{{ site.original.cover.url | relative_url }}" alt="Cover" class="cover-middle"/> 
{% endif %}

***

## 판매처

[Amazon]({{ site.original.store.amazon }})