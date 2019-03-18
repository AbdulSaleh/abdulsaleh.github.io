---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<ul>
<li > K.K. Maninis, J. Pont-Tuset, P. Arbeláez, and Van Gool
  <br><b>Convolutional Oriented Boundaries: From Image Segmentation to High-Level Tasks</b><br>
<i>IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</i>, vol. 40, no. 4, pp. 819 - 833, 2018.
<br />
<a href="javascript:toggleBibtex('Maninis2018')">[BibTeX]</a>
<a href="http://arxiv.org/abs/1701.04658" target="_blank">[PDF]</a> <a href="http://www.vision.ee.ethz.ch/~cvlsegmentation/cob/"  target="_blank">[Project Page]</a>
 
</li>
</ul>



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
