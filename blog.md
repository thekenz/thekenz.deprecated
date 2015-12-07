---
layout: page
title: Content
subtitle: A few of my thoughts.
title_image: /assets/img/titles/writing.png
---

<ul class="list-posts">
    {% for post in site.posts %}
        <li class="post-teaser">
            <a href="{{ post.url | prepend: site.baseurl }}">
                <span class="post-teaser__title">{{ post.title }}</span>
                <span class="post-teaser__date">{{ post.date | date: "%d %B %Y" }}</span>
            </a>
        </li>
    {% endfor %}
</ul>
