## 도서 정보

[원서 정보](original-book-info.html) / [정오표]({{ site.translated.errata.url }}) / [고객 지원]({{ site.github.issues_url }}/new/choose/) 

> {{ site.translated.description.long }}

* 도서명: [{{ site.translated.title.main }}]()
* 번역자: 
{% for author in site.translated.authors %}[{{ author[0] }}]({{ author[1]}}){% unless forloop.last%},{% endunless %}{% endfor %}
* 출판사: [{{ site.translated.publisher.name }}]({{ site.translated.publisher.url }})

***

## 새소식

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

***

## 판매처

[교보문고]({{ site.translated.store.kyobo }}) / [영풍문고]({{ site.translated.store.youngpoong }}) / [Yes24]({{ site.translated.store.yes24 }}) / [알라딘]({{ site.translated.store.aladin }}) / [인터파크]({{ site.translated.store.interpark }})

***

## 도움을 주신 분

[베타 리더](beta-readers.html)
