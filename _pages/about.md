---
permalink: /
title: "Jonas Latz"
excerpt: "Jonas Latz"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a mathematics PhD student in the group of [Elisabeth Ullmann](https://www-m2.ma.tum.de/bin/view/Allgemeines/Ullmann) at the Technical University of Munich. Our research is at the interface of numerical analysis, computational science, probability theory, and statistics. It focuses on methods that can be used to blend mathematical models with observational data.


 <table style="width:100%" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <th>Keywords, interests</th>
    <th> </th>
    <th> </th>
    <th> </th>
  </tr>
  <tr>
    <td>uncertainty quantification</td>
    <td>Bayesian inference</td>
    <td>inverse problems</td>
    <td>Markov chain Monte Carlo</td>
  </tr>
  <tr>
    <td>(stochastic) partial differential equations</td>
    <td>hierarchical models</td>
    <td>low-rank</td>
    <td>measures</td>
  </tr>
  <tr>
    <td>particle filters</td>
    <td>multilevel methods</td>
    <td>well-posedness</td>
    <td>random fields</td>
  </tr>
</table> 

This webpage contains information about my research output in [academic journals](/publications/) and at [academic meetings](/talks/). Moreover, I have summarised my [teaching experience](/teaching/) and my [personal background](/cv/). Input of any kind is highly appreciated; [please contact me](/contact/).

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

