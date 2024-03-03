---
layout: default
title: Archive
permalink: '/archive/'
---

<h3>Posts from 2024</h3>
{% for post in site.posts %}
{% assign post_date = post.date | date: "%B %-d, %Y" %}
{% assign post_year = post.date | date: "%Y" %}
{% if post_year == "2024" %}
<div class="posts-body">
    <a href="{{ post.url }}">{{ post.title }}</a>
    <p class="card-subtitle mb-2">{{ post_date }} • {{ post.reading_time }}</p>
</div>
{% endif %}
{% endfor %}
<h3>Posts from 2023 & older</h3>
{% for post in site.posts %}
{% assign post_date = post.date | date: "%B %-d, %Y" %}
{% assign post_year = post.date | date: "%Y" %}
{% if post_year != "2024" %}
<div class="posts-body">
    <a href="{{ post.url }}">{{ post.title }}</a>
    <p class="card-subtitle mb-2">{{ post_date }} • {{ post.reading_time }}</p>
</div>
{% endif %}
{% endfor %}