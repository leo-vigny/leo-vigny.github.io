---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

## Published work

 <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


## Working Papers

<ul>{% for post in site.workingpapers reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>