---
layout: page
permalink: /posts/javascript/
title: Posts about "javascript"
---

<div class="posts">
  {% for post in site.categories['javascript'] %}
    <article class="post">
      <h1>
          <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      </h1>
      <div>
        <p class="post_date">{{ post.date | date: "%B %e, %Y" }}</p>
      </div>
      <div class="entry">
        {{ post.excerpt }}
      </div>
      <a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}" class="read-more">
          Read More
      </a>
    </article>
  {% endfor %}
</div>