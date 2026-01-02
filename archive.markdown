---
layout: default
title: Archive
permalink: /archive/
---

<h1>Archive</h1>

{% assign postsByYear = site.posts | group_by_exp: "post", "post.date | date: '%Y'" %}

{% for year in postsByYear %}
  <h2>{{ year.name }}</h2>
  <ul class="post-list">
    {% for post in year.items %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d" }}</span>
        <a class="post-link" href="{{ post.url | relative_url }}">{{ post.title | escape }}</a>
      </li>
    {% endfor %}
  </ul>
{% endfor %}

