---
layout: default
---
# Index

Use the links below to navigate to all of the blog posts and community event pages. Click on the title at any point to return to this page.

If this is your first time visiting, please read the [Introduction]({{ "introduction.html" | absolute_url}}).

[//]: # "List of posts:"

## Project #6: Keep a Travel Blog
<ol>
	{% for post in site.posts reversed %}
	<li>
		<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
			<small><strong>{{ post.date | date: "%B %e, %Y" }}</strong></small>
	</li>
	{% endfor %}
</ol>

## Project #4: Attend and Participate in Community & Cultural Events

<ol>
	<li>
		<a href="/travelblog/community/lamancha.html">A Trip into La Mancha</a>
	</li>
	<li>
		<a href="/travelblog/community/manu.html">A Musical Community</a>
	</li>
	<li>
		<a href="/travelblog/community/flamenco.html">Flamenco: Spanish Tap Dance</a>
	</li>
	<li>
		<a href="/travelblog/community/bulls.html">A History of Bulls</a>
	</li>
</ol>
