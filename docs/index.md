## 도서 정보

>
> {{ site.translation.description.long }}
>

* 이름: [{{ site.translation.title.main }}]()
* 번역자: 
{% for author in site.translation.authors %}[{{ author[0] }}]({{ author[1]}}){% unless forloop.last%},{% endunless %}{% endfor %}
* 출판사: [{{ site.translation.publisher.name }}]({{ site.translation.publisher.url }})

[베타 리더](beta-readers.html) / [원서 정보](original-book-info.html) / [정오표]() / [오탈자 제보]()

* * *

## 새소식

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

* * *

## 판매처

[교보문고]() / [영풍문고]() / [Yes24]() / [알라딘]() / [인터파크]()