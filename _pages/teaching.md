---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

Polytech Nantes (2022-2023)
==

* Machine Learning for Computer Vision ([Visual Computing Master](https://polytech.univ-nantes.fr/fr/les-formations/masters-internationaux/visual-computing-masters-degree-vico))
* Perceptual Computing ([Visual Computing Master](https://polytech.univ-nantes.fr/fr/les-formations/masters-internationaux/visual-computing-masters-degree-vico))
* Data 2 ([Master Cultures Numériques](https://mcn.univ-nantes.fr/))

ESIR (2018-2020)
==

* Artificial Intelligence
Machine learning strategy; introduction to neural nets; introduction to deep learning; word embeddings; RNN; CNN; Markov decision processes; reinforcement learning.
* Databases
Relational model; relational calculus; conception (normalisation and modeling); ER model; complex queries.

ISTIC (2018-2020)
==
* Introduction to programming and Python

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
