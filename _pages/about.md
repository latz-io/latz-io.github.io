---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Welcome to my academic webpage. I am currently a PhD student in mathematics in the group of Elisabeth Ullmann at the Technical University of Munich. Our research is at the interface of numerical analysis, computational science, probability theory, and statistics. This page contains 

&nbsp; &nbsp; &nbsp;
---

# News



{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

