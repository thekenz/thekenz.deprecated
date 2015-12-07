---
layout: page
title: Contact
subtitle: Get in Touch with Me
title_image: /assets/img/titles/contact.png
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
