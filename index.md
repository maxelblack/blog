---
title: 主页
---
```html
<div style="color:white">
hope we can be as brave as each other.
</div>
```
<br />

{% for post in site.posts %}
## [{{post.title}}](/blog/{{post.url}})
<p>{{post.excerpt}}</p>...[More](/blog/{{post.url}})
<br />

{% endfor %}
