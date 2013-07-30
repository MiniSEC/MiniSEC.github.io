---
layout: page
title:
tagline: 
---
{% include JB/setup %}

<div class="row-fluid">
	<div class="span12">  
		{% for post in site.posts limit: 1 %}
			<h2>{{ post.title }}</h2>
			<h4>{{ post.date | date_to_long_string }}</h4>
			<p>
			<img src="{{post.image}}" width="40%" style="float:left;margin:0 5px 0 0;" />
			{{post.content}}
			</p>
			<a href="{{ BASE_PATH }}{{ post.url }}">Click here to Comment</a>
			<hr>
		{% endfor %}
	</div>
</div>

<div class="row-fluid">  
	<div class="span4">
		Last 5 Posts:
		<ul class="posts">
			{% for post in site.posts limit: 5 %}
				<li><span>{{ post.date | date_to_string }}</span> &raquo; <br> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
			{% endfor %}
		</ul>
	</div>  
	<div class="span4">
		<p>Something interesting here Soon!</p>
	</div>  
	<div class="span4">
		<p>About the Ministry</p>
	</div>  
</div> 

