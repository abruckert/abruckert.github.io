---
title: "Teaching"
permalink: /teaching/
author_profile: true
---

## Polytech Nantes (2022-2023)


* Machine Learning for Computer Vision ([Visual Computing Master](https://polytech.univ-nantes.fr/fr/les-formations/masters-internationaux/visual-computing-masters-degree-vico))
Machine learning basics; neural network; MLP; gradient methods; backpropagation; deep learning; CNN; RNN; applications in computer vision.   
[Slides](https://deep.univ-nantes.io/advnn/cours/1_introduction.html#/title-slide), <a href="https://github.com/abruckert/abruckert.github.io/blob/master/files/VICO_MLCV_Lab1.zip" download="download">Lab 1 material</a>, <a href="https://github.com/abruckert/abruckert.github.io/blob/master/files/VICO_MLCV_Lab2.zip" download="download">Lab 2 material</a>
* Perceptual Computing ([Visual Computing Master](https://polytech.univ-nantes.fr/fr/les-formations/masters-internationaux/visual-computing-masters-degree-vico))    
Human visual system; physiology of vision; perceptual principles; experimental methodology; visual attention; models of visual attention; image quality assessement.   
[Slides](https://github.com/abruckert/abruckert.github.io/blob/master/files/VICO_PC_VA_slides.zip), [Lab 1](https://github.com/abruckert/abruckert.github.io/blob/master/files/VICO_PC_VA_Lab1.ipynb), [Lab 2](https://github.com/abruckert/abruckert.github.io/blob/master/files/VICO_PC_VA_Lab2.ipynb), [Lab 3](https://github.com/abruckert/abruckert.github.io/blob/master/files/VICO_VICO_PC_VA_Lab3.zip), [Project](https://github.com/abruckert/abruckert.github.io/blob/master/files/VICO_PC_VA_project.pdf)

* Data 2 ([Master Cultures Numériques](https://mcn.univ-nantes.fr/))   
Introduction to machine learning; supervised vs non-supervised learning; regression vs classification problems; clustering algorithms; decision trees; SVM; complex data handling; introduction to neural nets.   
[Clustering](https://github.com/abruckert/abruckert.github.io/blob/master/files/CN_data2_clustering.pdf); [Lab 1](https://github.com/abruckert/abruckert.github.io/blob/master/files/TP1_clustering.zip)

## ESIR (2018-2020)


* Artificial Intelligence   
Machine learning strategy; introduction to neural nets; introduction to deep learning; word embeddings; RNN; CNN; Markov decision processes; reinforcement learning.
* Databases   
Relational model; relational calculus; conception (normalisation and modeling); ER model; complex queries.

## ISTIC (2018-2020)

* Introduction to programming and Python

Student Supervision
===
## Master students

* Yuan Feng, "Who looks at what ? Distinguishing and predicting personnal gaze behavior", Polytech Nantes (Feb.-July 2023)
* Jun Zhang, "Data augmentation for deep visual saliency models", Polytech Nantes (Feb.-July 2022)
* Supervisor of several Master students on their research projects

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
