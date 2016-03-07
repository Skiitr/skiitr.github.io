---
title: Blog
class: blogPage
weight: 2
---

<div class="home">

    <ul class="post">
      {% for post in site.posts %}
        <li class="post__item">
          <a class="post__title" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
          <p class="post__meta">{{ post.date | date: "%b %-d, %Y" }}{% if post.author %} • {{ post.author }}{% endif %}{% if post.meta %} • {{ post.meta }}{% endif %}</p>
          
          {{ post.excerpt }}

          <a class="btn--default" href="{{ post.url | prepend: site.baseurl }}">Read more</a>
        </li>
      {% endfor %}
    </ul>

</div>