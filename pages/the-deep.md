---
layout: page
permalink: /posts/the-deep/
title: The Deep
share-title: The Deep | Slice of Power
---

<p style="text-align: center;font-size: 18px;font-family: Gadugi;">Looking beyond our circumstances to gain more than what is presented to us. This page features valuable lessons and knowledge picked up from random events in life. A bad thing may not be a bad thing after all. Reflect from the deep and become a wiser you.</p>




<div class="posts">
  {% for post in site.categories['the-deep'] %}
    <article class="post">
      <h1>
          <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      </h1>
      <div>
        <p class="post_date">{{ post.date | date: "%B %e, %Y" }}</p>
      </div>
      <div class="entry">
        {{ post.excerpt }}
      </div>
      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">
          Read More
      </a>
    </article>
  {% endfor %}
</div>
