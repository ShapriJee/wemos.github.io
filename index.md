---
layout: default
title: Home
---

## Products
<div id="myCarousel" class="carousel slide">
   <!--  -->
   <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
   </ol>   
   <!--  -->
   <div class="carousel-inner">
      <div class="item active">
         <a href="/Products/d1_mini.html"> <img src="/Products/images/mini_v2.jpg" alt="D1 mini"></a>
      </div>
      <div class="item">
         <a href="/Products/d1_r2.html"><img src="/Products/images/r2_1.jpg" alt="D1 r2"></a>
      </div>
      <div class="item">
         <a href="/Products/oled_shield.html"><img src="/Products/images/oled_1.jpg" alt="OLED Shield"></a>
      </div>
   </div>
   <!--  -->
   <a class="carousel-control left" href="#myCarousel" 
      data-slide="prev">&lsaquo;</a>
   <a class="carousel-control right" href="#myCarousel" 
      data-slide="next">&rsaquo;</a>
</div>

## Blog

  <ul class="posts">
    {% for post in site.posts limit:3 %}
      <li><span>{{ post.date|date: "%Y-%m-%d"  }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
    <li><a href="/blog.html">All</a></li>
  </ul>

## Tutorial
- [Get started in Arduino](/Tutorial/get_started_in_arduino.html)
- [Get started in NodeMCU](/Tutorial/get_started_in_nodemcu.html)
- [More...](/Tutorial/)
