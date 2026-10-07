---
layout: page
title: "Posts"
permalink: /blog/
---

This page contains a record of all posts made by me, this includes stuff such as my research experiences, internship experiences and other extraneous posts

[comment]: <> (This part and the posts i used google to help me as i couldnt find out how to get my posts to appear on my own)

{% for post in site.posts %}
  <p><a href="{{ post.url }}">{{ post.title }}</a></p>
{% endfor %}
