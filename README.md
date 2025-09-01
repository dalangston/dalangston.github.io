# dalangston.github.io

### Posts

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }}) {{ post.date }}
{{ post.excerpt }}
{% for tag in post.tags %} {{ tag }} {% endfor %}


{% endfor %}
