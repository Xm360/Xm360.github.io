---
layout: default
title: cm-itsys.de:Start
active: Start
---

<h3>Aktuelles</h3>
<div>
  {% for post in site.posts limit: 3 %}
    <div class="col-lg-4">    
      <h4><a href="{{ post.url }}">{{ post.title}}</a></h4>
	<span>{{ post.date | date_to_string }}</span><br>
      <p>{{ post.excerpt }}</p>
    </div>    
  {% endfor %}
</div>
<br>
<br>
<div class="pull-right">
<p><a class="btn btn-sm btn-info" href="/allpostings.html" role="button">Alle Beiträge</a></p>
</div>
