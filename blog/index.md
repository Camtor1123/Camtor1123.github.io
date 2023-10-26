---
title: Bienvenido a mi Blog
---
<h1>Post</h1>
 <p> {% for post in site.posts %}
      {{ post.date | date: "%-d %B %Y"}}<br>
      <a href="{{ post.url }}">{{ post.title }}</a>
  {% endfor %}
 </p>
