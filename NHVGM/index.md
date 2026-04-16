---
layout: page
title: I’m Not a Hidden Villain, I’m a Gate Master
tag: [nhvgm]
---

test

<p>
  Tagged 
  {% for tag in page.tags %}
  <a class="post" href="/tag/{{tag}}">#{{tag}}</a>{% unless forloop.last %}, {% endunless %}
  {% endfor %}
</p>
