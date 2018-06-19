---
layout: default
---

Click on the title at any point to return to this page.

If this is your first time visiting, please read the [Introduction]({{ "introduction.html" | absolute_url}}).

[//]: # "List of posts:"

# Project #6: Keep a Travel Blog
<ol>
	{% for post in site.posts reversed %}
	<li>
		<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
			<small><strong>{{ post.date | date: "%B %e, %Y" }}</strong></small>
	</li>
	{% endfor %}
</ol>

# Project #4: Attend and Participate in Community & Cultural Events

<ol>
	<li>
		<a href="/travelblog/community/lamancha.html">A Trip into La Mancha</a>
	</li>
</ol>
