---
layout: default
---

Click on the header at any point to return to this page.

If this is your first time visiting, read the [Introduction].

[//]: # "List of posts:"
<ol>
{% for post in site.posts reversed %}
<li>
<a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
<small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . </small> <!--  . -->
	    <!-- <a href="http://erjjones.github.com{{ post.url }}#disqus_thread"></a></small></p> -->
</li>
{% endfor %}
</ol>

## Introduction

- Background on the CEP program
- Background on me
- Explanation of this project
