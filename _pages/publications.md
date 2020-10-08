---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Publications
======
* K.G. Schilling, ... S. Warrington, et al., “Tractography dissection variability: what happens when 42 groups dissect 14 white matter bundles on the same dataset?”, <i>bioRxiv</i>, 2020.' [10.1101/2020.10.07.321083v1](https://www.biorxiv.org/content/10.1101/2020.10.07.321083v1)
* M. Helmer, S. Warrington, A.-R. Mohammadi-Nejad, J. L. Ji, A. Howell, B. Rosand, A. Anticevic,S. N. Sotiropoulos, and J. D. Murray, “On stability of canonical correlation analysis and partial least squares with application to brain-behavior associations”, <i>bioRxiv</i>, 2020. [10.1101/2020.08.25.265546](https://www.biorxiv.org/content/10.1101/2020.08.25.265546v1).
* S. Warrington, K. L. Bryant, A. A. Khrapitchev, J. Sallet, M. Charquero-Ballester, G. Douaud, S. Jbabdi, R. B. Mars, and S. N. Sotiropoulos, “XTRACT - standardised protocols for automated tractography in the human and macaque brain”, <i>NeuroImage</i>, vol. 217, 2020. [10.1016/j.neuroimage.2020.116923](https://www.sciencedirect.com/science/article/pii/S1053811920304092).
* E. Peake, S. Warrington, N. J. Dudley, P. S. Morgan, and N. M. Gibson, “A Method of Correcting for the Effect of Temperature on Low-Contrast Penetration Measurement in Urethane Phantoms”, <i>Ultrasound in Medicine and Biology</i>, vol. 45, no. 6, 2019. [10.1016/j.ultrasmedbio.2019.02.012](https://www.umbjournal.org/article/S0301-5629(19)30079-1/abstract)



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
