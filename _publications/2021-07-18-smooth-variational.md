---
title: "Smooth Variational Graph Embeddings for Efficient Neural Architecture Search"
collection: publications
permalink: /publication/2021-07-18-smooth-variational
date: 2021-07-18
venue: ' International Joint Conference on Neural Networks'
paperurl: 'https://ieeexplore.ieee.org/document/9534092'
authors: '<b>Jovita Lukasik</b>, David Friede, Arber Zela, Frank Hutter, Margret Keuper'
arxiv: 'https://arxiv.org/pdf/2010.04683' 
code: https://github.com/jovitalukasik/SVGe
bibtex: true
teaser: previews/LukasikIJCNN2021.png
---
{{ page.authors }}

<img class="pub_teaser" src="../images/previews/LukasikIJCNN2021.png" alt="Teaser Image" title="teaser" />

## Abstract 

>Neural architecture search (NAS) has recently been addressed from various directions, including discrete, sampling-based methods and efficient differentiable approaches. While the former are notoriously expensive, the latter suffer from imposing strong constraints on the search space. Architecture optimization from a learned embedding space for example through graph neural network based variational autoencoders builds a middle ground and leverages advantages from both sides. Such approaches have recently shown good performance on several benchmarks. Yet, their stability and predictive power heavily depends on their capacity to reconstruct networks from the embedding space. In this paper, we propose a two-sided variational graph autoencoder, which allows to smoothly encode and accurately reconstruct neural architectures from various search spaces. We evaluate the proposed approach on neural architectures defined by the ENAS approach, the NAS-Bench-101 and the NAS-Bench-201 search space and show that our smooth embedding space allows to directly extrapolate the performance prediction to architectures outside the seen domain (e.g. with more operations). Thus, it facilitates to predict good network architectures even without expensive Bayesian optimization or reinforcement learning.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 

      @inproceedings{Lukasik2021svge,
         author={Lukasik, Jovita and Friede, David and Zela, Arber and Hutter, Frank and Keuper, Margret},
          booktitle={2021 International Joint Conference on Neural Networks (IJCNN)}, 
          title={Smooth Variational Graph Embeddings for Efficient Neural Architecture Search}, 
          year={2021}}



