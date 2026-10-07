---
layout: default
---

# Home
## Aries Sauerhaft
Welcome to my portfolio, I am a **Physics major** with a minor in **Astrophysics** at the University of Connecticut, I am expected to graduate by Spring of 2029. My current GPA is 3.052.
### About Me

### My Posts
<!-- This part and the posts i used google to help me as i couldnt find out how to get my posts to appear on my own -->
{% for post in site.posts %}
  {% if post.sticky == true %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  {% endif %}
{% endfor %}

{% for post in site.posts %}
  {% if post.sticky != true %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  {% endif %}
{% endfor %}





