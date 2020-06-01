---
layout: simple
title: cm-itsys.de:Übersicht
---
<div id="allpostings">
  <h1>Übersicht der Beiträge</h1>
<br>
	<br>
<ul>
  {% for post in site.posts %}
    <li>
	<span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a>
   </li>
  {% endfor %}
</ul>

</div>
