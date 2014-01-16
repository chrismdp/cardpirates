---
layout: default
title: "Blog"
---

{% for post in site.posts %}

<h2><a href='{{ post.url}}'>{{ post.title }}</a></h2>
<p class="meta">{{ post.date | date_to_string }} by {{ post.author }}</p>

<div class='post'>
  {{ post.content }}
</div>

<br/>

{% endfor %}

