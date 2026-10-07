---
layout: default
title: "Posts"
permalink: /blog/
---
# Posts

This page contains a record of all posts made by me, this includes stuff such as my research experiences, internship experiences and other extraneous posts

[comment]: <> (This part and the posts i used google to help me as i couldnt find out how to get my posts to appear on my own)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="post-date">- {{ post.date | date: "%B %d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
