---
layout: page
title: Archive
---

<div class="archive-list">
	<h1>Data Beauty</h1>
	<p>
	  <h3>Archive</h3>
	</p>
	<ul class="listing">
		{% for post in site.posts %}
		<li class="listing-item">
		  <time datetime="{{ post.date | date: "%m-%d-%Y" }}">{{ post.date | date: "%m-%d-%Y" }}</time>
		  <a href="{{ post.url }}" class="title">{{ post.title }}</a>
		</li>
		{% endfor %}
	</ul>
</div>
