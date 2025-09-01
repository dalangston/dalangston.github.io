# dalangston.github.io

### Posts

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }}) {{ post.date | date: "%-d %B %Y %H:%M" }}
{{ post.excerpt }}
{% for tag in post.tags %} {{ tag }} {% endfor %}


{% endfor %}
