# Jaylin's Blog

## Heading 2

Hello everyone and *welcome* to my blog.
Here I will about talk about my  journey in full stack development.

![A professional photo of me](/assets/)

## recent posts
<ul>
{% for post in site.posts %}
<li>
<a href="/blog{{ post.url}}">{{ post.title}}</a>
</li>
{% endfor %}
</ul>