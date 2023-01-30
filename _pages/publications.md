---
title: "Publications"
permalink: /publications/
author_profile: true
---

## Peer-reviewed journal publications

I. Goudé\*, **A. Bruckert**\*, A. H. Olivier, J. Pettré, R. Cozot, K. Bouatouch, M. Christie, and L. Hoyet. [Real-time Multi-map Saliency-driven Gaze
Behavior for Non-conversational Characters](https://hal.archives-ouvertes.fr/hal-03796523/) *IEEE Transactions on Visualization and Computer Graphics*, 2023.

**A. Bruckert**, M. Christie, O. Le Meur, [Where to look at the movies: Analyzing visual attention to understand movie editing](https://link.springer.com/article/10.3758/s13428-022-01949-7), *Behavior Research Methods*, 2022.

**A. Bruckert**, H. R. Tavakoli, Z. Liu, M. Christie, O. Le Meur, [Deep saliency models: The quest for the loss function](https://www.sciencedirect.com/science/article/pii/S0925231220313734), *Neurocomputing*, vol.453, pp.693-704, 2021.


## International conferences

**A. Bruckert**, Y. H. Lam, M. Christie, O. Le Meur, [Deep learning for inter-observer congruency prediction](https://ieeexplore.ieee.org/abstract/document/8803596), *IEEE ICIP*, pp. 3766-3770, 2019.

M. Poncet, A. Basset, S. Farrens, **A. Bruckert**, M. Gray, D. Vibert, A. Schmitt, S. Jamal, V. Le Brun, O. Le Fèvre, C. Surace, M. Huertas-Company, H. Dole, E. Soubrié, R. Peralta, R. Cabanac, [Euclid: AI in the dark space](https://dx.doi.org/10.2760/848593), *Big Data from Space*, pp.9-14, 2019.

## Preprints, work-in-progress

**A. Bruckert**, M. Abid, M. Perreira da Silva, and P. Le Callet. Could the bubbleview metaphor be used to infer visual attention on 3d graphical content ? *Submitted to International Conference on Accoustics, Speech and Signal Processing (ICASSP)*, 2023.

## Thesis

**A. Bruckert**, [A perceptual approach to film editing : exploring cinematography through visual attention and computational saliency](https://ged.univ-rennes1.fr/nuxeo/site/esupversions/45936f86-1136-478e-8404-ebaf73a90007?inline), Université Rennes 1, 2022

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
