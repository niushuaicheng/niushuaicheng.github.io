---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Received my Bachelor Degree in Mathematics and Applied Mathematics in 2018 from Southwest Jiaotong University in Chengdu, China. Currently I am a Ph.D candidate of Software Engineering in South China University of Technology in Guangzhou, China. My supervisors are Prof. Mingkui Tan (SCUT) and Dr. Peilin Zhao (Tencent AI Lab). My research interests include Deep Learning, Online Learning, Neural Network Architecture Search and Reinforcement Learning.

Publications
======
<div>
  <table>
  {% for post in site.publications reversed %}
    <tr>{% include publication.html %}</tr>
  {% endfor %}
  </table>
</div>

<div margin-bottom:100px>
  <a href="/publications/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div> 


Presentations
======
<div>
  <table>
  {% for post in site.talks reversed %}
    <tr>{% include archive-single-talk-cv.html %}</tr>
  {% endfor %}
  </table>
</div>

<div margin-bottom:100px>
  <a href="/talks/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div> 

Projects
======
<div>
  <table>
  {% for post in site.projects reversed %}
    <tr>{% include archive-single-teach.html %}</tr>
  {% endfor %}
  </table>
</div>

<div margin-bottom:100px>
  <a href="/projects/">
    <button class="btn btn--readmore">Read more <font size="1">>></font></button>
  </a>
</div> 

