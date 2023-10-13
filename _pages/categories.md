---
layout: page
permalink: /categories/
title: Categories
---
<div id="archives" style = "font-family: 'Fredericka the Great';" >
<!-- <table style="border: 1px dashed;"> -->
{% for category in site.categories %}
<div class="archive-group" >
  {% capture category_name %}{{ category | first }}{% endcapture %}
  <div id="#{{ category_name | slugize }}" ></div>
  <h3 class="category-head" >{{ category_name }}</h3>
  <a name="{{ category_name | slugize }}"></a>
  {% for post in site.categories[category_name] %}
  <article class="archive-item">
    <h4>
        <a href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a>
    </h4>
  </article>
  {% endfor %}    
</div>
{% endfor %}
</div>
<br><br>
<style>
  #archives {
    margin-bottom:10px;
    padding: 10px 10px;
  }
  .archive-group {
    float: left;
    width:45%;
    padding: 10px 10px;
    border:0.5px dotted ;
    margin-right:10px;
    margin-bottom:10px;
    align-items:center;
  }
  .archive-item {
    background-color: var(--paper-color-less);
    border:1px dashed;
    padding: 5px;
    font-size:14px
  }
  .archive-item:nth-child(n+2) {
    margin-top: -1px;
  }


</style>