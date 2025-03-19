---
layout: blog
title: "CTF writeups Posts"
permalink: /ctf/
---

<ul class="posts">
    {% for post in site.categories.ctf %}
        <li>
            <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
            ::
            <a class="post-link" href="https://keiz44l.github.io{{ post.url }}">{{ post.title }}</a>
            @ {
            {% assign tag = post.tags | sort %}
            {% for category in tag %}<span><a href="{{ site.baseurl }}category/#{{ category }}" class="reserved">{{ category }}</a>{% if forloop.last != true %},{% endif %}</span>{% endfor %}
            {% assign tag = nil %}
            }
        </li>
    {% endfor %}
</ul>
