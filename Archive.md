---
layout: page
title: Lore of Uramar
---

<ul class="related-posts">
    {% for post in site.posts %}
          <p>
          <a href="{{ post.url }}">
            {{ post.title }}
            </a>
            <small>{{ post.date | date_to_string }}</small>
          </p>
    {% endfor %}
</ul>
