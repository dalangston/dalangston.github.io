# dalangston.github.io

### Posts

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }}) {{ post.date }}
{{ post.excerpt }}
{% for cat in post.categories %} {{ cat }} {% endfor %}


{% endfor %}
