---
layout: page
title: About
description: 代码改变世界
keywords: Rongjie Ma, 马荣杰
comments: true
menu: 关于
permalink: /about/
---

I am Ma Rongjie, born of code and code.

Admiring the "art of elegant coding."

Firmly believe that practice makes perfect and strives to change lives.

## Contact information

{% for website in site.data.social %}
* {{ website.sitename }}：[@{{ website.sitename }}]({{ website.url }})
{% endfor %}

## Skill Keywords

{% for category in site.data.skills %}
### {{ category.name }}
<div class="btn-inline">
{% for keyword in category.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}

![](/images/posts/blog/1.png)
