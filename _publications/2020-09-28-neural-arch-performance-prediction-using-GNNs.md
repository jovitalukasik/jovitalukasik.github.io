---
title: "Neural Architecture Performance Prediction Using Graph Neural Networks"
collection: publications
permalink: /publication/2020-09-28-neural-arch-performance-prediction-using-GNNs
date: 2020-09-28
venue: 'DAGM German Conference on Pattern Recognition'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-71278-5_14'
authors: '<b>Jovita Lukasik</b>, David Friede, Heiner Stuckenschmidt, Margret Keuper'
bibtex: true
teaser: /previews/LukasikGCPR2020.png
arxiv: 'https://arxiv.org/abs/2010.10024'
code: https://github.com/jovitalukasik/GNN_predictor
---
{{ page.authors }}

<img class="pub_teaser" src="../images/previews/LukasikGCPR2020.png" alt="Teaser Image" title="teaser" />

## Abstract 

>In computer vision research, the process of automating architecture engineering, Neural Architecture Search (NAS), has gained substantial interest. Due to the high computational costs, most recent approaches to NAS as well as the few available benchmarks only provide limited search spaces. In this paper we propose a surrogate model for neural architecture performance prediction built upon Graph Neural Networks (GNN). We demonstrate the effectiveness of this surrogate model on neural architecture performance prediction for structurally unknown architectures (i.e. zero shot prediction) by evaluating the GNN on several experiments on the NAS-Bench-101 dataset.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 

    @inproceedings{Lukasik2020neuralperfpred,
      title = {Neural Architecture Performance Prediction Using Graph Neural Networks},
      author = {Lukasik, Jovita and Friede, David and Stuckenschmidt, Heiner and Keuper, Margret},
      booktitle={Pattern Recognition},
      year={2020}}
