---
title: 主页
---
<div style="font-color:blue;font-size:1.5em">
Hope we can be as brave as each other.
</div>

<br />
{% for post in site.posts %}
## [{{post.title}}](/blog/{{post.url}})
<p>{{post.excerpt}}</p>...[More](/blog/{{post.url}})
<br />

{% endfor %}
