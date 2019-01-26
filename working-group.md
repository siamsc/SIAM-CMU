---
layout: post
title:  "Working group"
published: true
---
Our working group meets every Thursday at 3:30pm in WEH 7201. Cookies and coffee are provided.

<ul class="post-list">
  {% for post in site.categories.working %}
    <li>
      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>
      <span class="post-meta">{{ post.author }}</span>
    </li>
  {% endfor %}
</ul>
