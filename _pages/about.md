---
permalink: /
title: "Jonas Latz"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



This webpage is currently under construction. Please visit www.latz.io




{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

