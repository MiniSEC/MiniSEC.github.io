---
layout: page
title:
tagline: 
---
{% include JB/setup %}

Here's the newest Post.

<div class="row">
	<div class="span12">  
		{% for post in site.posts limit: 1 %}
			<h2>{{ post.title }}</h2>
			<h4>{{ post.date | date_to_long_string }}</h4>
			<p>
			<img src="{{post.image}}" width="40%" style="float:left;margin:0 5px 0 0;" />
			{{post.content}}
			</p>
		{% endfor %}
	</div>
</div>

<div class="row">  
	<div class="span4">
		<p>Here's Posts</p>
		<ul class="posts">
			{% for post in site.posts %}
			<li>
				<span>{{ post.date | date_to_string }}</span> &raquo; <br> <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
			{% endfor %}
		</ul>
	</div>  
	<div class="span4">
		<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Nam cursus. Morbi ut mi. Nullam enim leo, egestas id, condimentum at, laoreet mattis, massa. Sed eleifend nonummy diam. Praesent mauris ante, elementum et, bibendum at, posuere sit amet, nibh. Duis tincidunt lectus quis dui viverra vestibulum. Suspendisse vulputate aliquam dui. Nulla elementum dui ut augue. Aliquam vehicula mi at mauris. Maecenas placerat, nisl at consequat rhoncus, sem nunc gravida justo, quis eleifend arcu velit quis lacus. Morbi magna magna, tincidunt a, mattis non, imperdiet vitae, tellus. Sed odio est, auctor ac, sollicitudin in, consequat vitae, orci. Fusce id felis. Vivamus sollicitudin metus eget eros.</p>
	</div>  
	<div class="span4">
		<p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Nam cursus. Morbi ut mi. Nullam enim leo, egestas id, condimentum at, laoreet mattis, massa. Sed eleifend nonummy diam. Praesent mauris ante, elementum et, bibendum at, posuere sit amet, nibh. Duis tincidunt lectus quis dui viverra vestibulum. Suspendisse vulputate aliquam dui. Nulla elementum dui ut augue. Aliquam vehicula mi at mauris. Maecenas placerat, nisl at consequat rhoncus, sem nunc gravida justo, quis eleifend arcu velit quis lacus. Morbi magna magna, tincidunt a, mattis non, imperdiet vitae, tellus. Sed odio est, auctor ac, sollicitudin in, consequat vitae, orci. Fusce id felis. Vivamus sollicitudin metus eget eros.</p>
	</div>  
</div> 

