---
layout: page
title: News application
description: Algunas aplicaciones en la que participé
permalink: /newsapp/
---
<style>
.post-list h2 { margin-bottom: 0; }
</style>

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <!--<span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>-->
      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>
      <span class="post-meta">{{ post.description }}</span>
    </li>
  {% endfor %}
</ul>
<!--
<p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>
-->
