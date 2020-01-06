---
permalink: /
title: "Input/output"
excerpt: "Input/output"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Jonas Latz; welcome to my webpage! 

Currently, I am a Research Associate in the [Department of Applied Mathematics and Theoretical Physics, University of Cambridge](http://damtp.cam.ac.uk), where I am working with [Carola-Bibiane Schönlieb](http://www.damtp.cam.ac.uk/user/cbs31/Home.html). Moreover, I am part of the [Cambridge Image Analysis group](http://www.damtp.cam.ac.uk/research/cia/) and the EPSRC-funded project [PET++](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/S026045/1). 

The research I am involved in is at the interface of numerical analysis, computational science, probability theory, and statistics. It focuses on methods that can be used to blend mathematical models with observational data.  


 <table style="width:100%; border: none;" border="0" cellspacing="0" cellpadding="0">
  <tr>
    <th colspan="4" style="border: none;">Keywords.</th>
    <th colspan="4" style="border: none;"> </th>
    <th colspan="4" style="border: none;"> </th>
  </tr>
  <tr>
    <td colspan="4" style="border: none;">Uncertainty quantification</td>
    <td colspan="4" style="border: none;" align="center">Bayesian inference</td>
    <td colspan="4" style="border: none;" align="right">Inverse problems</td>
  </tr>
  <tr>
        <td colspan="4" style="border: none;">Well-posedness</td>
    <td colspan="4" style="border: none;" align="center">Measures and integration</td>
       <td colspan="4" style="border: none;" align="right">Markov chain Monte Carlo</td>
  </tr>
  <tr>
    <td colspan="4" style="border: none;">Particle filters</td>
        <td colspan="4" style="border: none;" align="center">Real world data</td>
        <td colspan="4" style="border: none;" align="right">Low-rank approximation</td>
  </tr>
    <tr>
    <td colspan="4" style="border: none;">Multilevel methods</td>
          <td colspan="4" style="border: none;" align="center">Hierarchical models</td>
  <td colspan="4" style="border: none;" align="right">(Stochastic) partial differential equations</td>
  </tr>
</table> 

<hr>

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

