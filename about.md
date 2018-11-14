---
title:  "Test About!"
food: Pizza
---

# this is a test about page

is it working?
can I [link to stuff?](other)

## posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
