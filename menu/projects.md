---
layout: page
title: Projects
permalink: /projects
---

<ul class="posts">
  {% for post in site.posts %}
    {% if post.category contains 'projects' %}
       {% comment %}
        {% unless post.next %}
          <h3>{{ post.date | date: '%Y' }}</h3>
        {% else %}
          {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
          {% capture nyear %}{{ post.next.date | date: '%Y' }}{% endcapture %}
          {% if year != nyear %}
            <h3>{{ post.date | date: '%Y' }}</h3>
          {% endif %}
        {% endunless %}
        {% endcomment %}

        <li itemscope>
          <a href="{{ site.github.url }}{{ post.url }}">{{ post.title }}</a>
          <p class="post-date"><span><i class="fa fa-calendar" aria-hidden="true"></i> {{ post.date | date: "%Y %b %-d" }} - <i class="fa fa-clock-o" aria-hidden="true"></i> {% include read-time.html %}</span></p>
        </li>
    {% endif %}
  {% endfor %}
</ul>