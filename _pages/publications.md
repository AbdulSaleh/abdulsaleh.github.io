---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


<li ><p>
<a href="http://www.vision.ee.ethz.ch/~kmaninis" target="_blank">K.K. Maninis</a>, J. Pont-Tuset, <a href="https://biomedicalcomputervision.uniandes.edu.co" target="_blank">P. Arbeláez</a> and <a href="http://www.vision.ee.ethz.ch/members/get_member.cgi?id=1" target="_blank">L. Van Gool</a><br><b>Convolutional Oriented Boundaries: From Image Segmentation to High-Level Tasks</b><br>
<i>IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)</i>, vol. 40, no. 4, pp. 819 - 833, 2018.
<br />
<a href="javascript:toggleBibtex('Maninis2018')">[BibTeX]</a>
<a href="http://arxiv.org/abs/1701.04658" target="_blank">[PDF]</a> <a href="http://www.vision.ee.ethz.ch/~cvlsegmentation/cob/"  target="_blank">[Project Page]</a>
</p>
<div id="bib_Maninis2018" class="bibtex noshow">
<pre>
@article{Maninis2018,
  author = {Maninis, Kevis-Kokitsi and Pont-Tuset, Jordi and Arbel&aacute;ez, Pablo and {Van Gool}, Luc},
  title = {Convolutional Oriented Boundaries: From Image Segmentation to High-Level Tasks},
  journal = {IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)},
  year = {2018},
  volume = {40},
  number = {4},
  pages = {819 - 833}
}
</pre>
</div>
</li>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
