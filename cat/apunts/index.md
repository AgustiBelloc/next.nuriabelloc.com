---
layout: page
title: Apunts
description: Apunts de Shiatsu
menu: false
# sibling: notes
---
<div class="list-group">
  {% for post in site.posts %}
    <a href="{{ post.url }}" class="list-group-item">
      <span class="badge">
        <time>{{ post.date | date_to_string }}</time>
      </span>
      <h4 class="list-group-item-heading">{{ post.title }}</h4>
      <p class="list-group-item-text">{{ post.excerpt | strip_html }}</p>
    </a>
  {% endfor %}
</div>

---

+ [Stacked paper sheets effect with css3](http://jsfiddle.net/YZ62u/)
+ [Pure CSS3 Paper Curls Without Images](http://blogs.sitepointstatic.com/examples/tech/css3-paper-curl/index.html)
