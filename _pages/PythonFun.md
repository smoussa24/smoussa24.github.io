---
layout: single
author_profile: true
permalink: /Pythonfun/
classes: wide
---

<p>
</p>

Let's Code  
====================
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

<ul>
  {% for post in site.categories.pythonfuncode %}
      <li>
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
      </li>
   {% endfor %}
</ul>

<p align="justify">
