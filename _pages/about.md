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

___

 <table style="width:100%; border: none;" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <th colspan="4" style="border: none;">Keywords.</th>
    <th colspan="4" style="border: none;"> </th>
    <th colspan="4" style="border: none;"> </th>
  </tr>
  <tr>
    <td colspan="4" style="border: none;">uncertainty quantification</td>
    <td colspan="4" style="border: none;" align="center">Bayesian inference</td>
    <td colspan="4" style="border: none;" align="right">inverse problems</td>
  </tr>
  <tr>
        <td colspan="4" style="border: none;">well-posedness</td>
    <td colspan="4" style="border: none;" align="center">measure theory</td>
       <td colspan="4" style="border: none;" align="right">Markov chain Monte Carlo</td>
  </tr>
  <tr>
    <td colspan="4" style="border: none;">particle filters</td>
    <td colspan="4" style="border: none;" align="center">hierarchical models</td>
        <td colspan="4" style="border: none;" align="right">low-rank approximation</td>
  </tr>
    <tr>
    <td colspan="4" style="border: none;">multilevel methods</td>
    <td colspan="4" style="border: none;" align="center">machine learning</td>
  <td colspan="4" style="border: none;" align="right">(stochastic) partial differential equations</td>
  </tr>
</table> 

___

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

