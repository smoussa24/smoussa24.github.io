---
layout: single
author_profile: true
permalink: /Portfolio/
classes: wide
---

<p>  
</p>

Portfolio
====================
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
<style>

.grid-container {
  display: grid;
  grid-template-columns: 49% 49%;
  background-color: #ffffff;
  padding: 10px;
}
.grid-item {
  background-color: #ffffff;
  border: 0px solid #ffffff;
  padding: 10px;
  text-align: center;
}

</style>

<p align="justify">
