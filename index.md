---
title: 主页
---
<div style="color:blue;font-size:1.1em">
# hope we can be as brave as each other._
</div>
<br />

{% for post in site.posts %}
## [{{post.title}}](/blog/{{post.url}})
<p>{{post.excerpt}}</p>...[More](/blog/{{post.url}})
<br />

{% endfor %}
