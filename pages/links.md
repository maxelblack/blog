---
layout: mypost
title: 友情链接
---

欢迎各位互添友链，如需添加请到 [GitHub 仓库](https://github.com/maxelblack/blog)提交一个 issue ，我看到后会添加并删除该 issue ， 若发现 issue 被删除不必顾虑。

#### 本站的友链信息

```
名称：{{ site.title }}
描述：{{ site.description }}
地址：{{ site.domainUrl }}{{ site.baseurl }}
头像：{{ site.domainUrl }}{{ site.baseurl }}/static/img/logo.jpg
```

<ul>
  {%- for link in site.links %}
  <li>
    <p><a href="{{ link.url }}" title="{{ link.desc }}" target="_blank" >{{ link.title }}</a></p>
  </li>
  {%- endfor %}
</ul>
