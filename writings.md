---
layout: page
permalink: /writings/
---

<style>
  .writings-list {
    list-style: none;
    padding: 0;
    margin-top: 20px;
  }
  .writings-list li {
    margin-bottom: 12px;
    font-size: 1.15rem;
  }
</style>

<ul class="writings-list">
{% assign poems = site.poems | sort: 'date' | reverse %}
{% for poem in poems %}
  <li><a href="{{ poem.url | relative_url }}">{{ poem.title }}</a></li>
{% endfor %}
</ul>