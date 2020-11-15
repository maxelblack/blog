---
title: 主页
---
```html
<div style="color:white">
Hope we can be as brave as each other.
</div>
```

{% for post in site.posts %}
## [{{post.title}}](/blog/{{post.url}}
)
<p>{{post.excerpt}}</p>...[More](/blog/{{post.url}})
<br />

{% endfor %}
