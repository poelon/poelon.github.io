---
layout: post
title:  "planètes et signes"
date:   2017-12-25 16:35:55 +0100
categories: jekyll update
---
site 
[le monde](http://lemonde.fr/)
<li>lune<img src="/assets/img/planetes/moon-celestial.jpg" alt="lune"></li>
{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
![Alt text]({{ myimage.path  | absolute_url }})
{% endfor %}
