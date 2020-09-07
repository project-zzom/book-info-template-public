## 번역서 정보

> {{ site.translated.description.long }}

* 도서명: [{{ site.translated.title.main }}]()
* 번역자: {% for author in site.data.authors-translated %}[{{ author.name }}]({{ author.profile }}){% unless forloop.last%}, {% endunless %}{% endfor %}
* 출판사: [{{ site.translated.publisher.name }}]({{ site.translated.publisher.url }})

***

## 새소식

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

***

## 판매처

{% for store in site.data.stores-translated %}<a href="{{ store.link }}" target="{{ store.target }}">{{ store.name }}</a>{% unless forloop.last%} / {% endunless %}{% endfor %}