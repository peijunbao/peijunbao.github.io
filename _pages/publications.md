<--.
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
<img src='./images/DepNet.jpg' width="800" height="300">

<i><strong><font size="5" >A</font></strong></i>  
<strong>B</strong>, C  
<i>D</i>,  
[[E]()]   
<br/><img src='/images/.jpg' width="800" height="300">  
<font size="4" color="gray">F</font>
