{% for post in post.tags.sports %}    
	<li><a href="{{ post.url }}">{{ post.title }}</a></li>    
{% endfor %}