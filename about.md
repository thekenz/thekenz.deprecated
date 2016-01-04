---
layout: page
title: About
subtitle: Just who the hell you think I am?
permalink: /about/
---

<ul class="list-posts">
    {% for project in site.work %}
        <li class="post-teaser">
            <a href="{{ project.url | prepend: site.baseurl }}">
                <span class="post-teaser__title">{{ page.title }}</span>
            </a>
        </li>
    {% endfor %}
</ul>
