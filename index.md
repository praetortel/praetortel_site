---
layout: default
title: "Welcome"
---
<div class="container">
  <div class="column">
    <h3><u>Recent Musings</u></h3>
    <ul>
      {% for post in site.posts %}
        <li>
          <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
      {% endfor %}
    </ul>
  </div>

  <div class="column">
    <h3><u>Sub-sites</u></h3>
    <ul>
      {% for site in site.data.subsites %}
        <li><a href="{{site.url}}">{{ site.name }}</a></li>
      {% endfor %}
    </ul>
  </div>
</div>
