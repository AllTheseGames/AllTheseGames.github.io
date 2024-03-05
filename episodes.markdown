---
layout: page
title: Episodes
permalink: /episodes/
---

{% assign sorted = site.episodes | reverse %}
{% for episode in sorted %}

<ul class="post-list">
    <li>
    <span class="post-meta">{{ episode.date | date: "%d %b, %y" }}</span>
        <h3>
          <a class="post-link" href="{{ episode.url }}">
            {{ episode.title }}
          </a>
        </h3>
    </li>
</ul>

{% endfor %}