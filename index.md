---
layout: default
---

{% if site.posts.size > 0 %}
<div class="latest-entry">
	<header>
		<h1>{{ site.posts[0].title }}</h1>
		<p class="entry-info">Published: {{ site.posts[0].date | date: "%Y-%m-%d" }}</p>
	</header>
	<div class="entry-body">
		{{site.posts[0].content}}
	</div>
</div>
{% endif %}
