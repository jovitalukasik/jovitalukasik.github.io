---
title: "Layered Quantum Architecture Search for 3D Point Cloud Classification"
collection: publications
permalink: /publication/2026-03-26_Quantum_NAS
date: 2026-03-26
venue: 'International Conference on 3D Vision'
paperurl: 'https://openreview.net/pdf?id=GfTl5ToYrn'
authors: 'Natacha Kuete Meli, <b>Jovita Lukasik</b>, Vladislav Golyanik, Michael Moeller'
bibtex: true
teaser: /previews/Kuete3DV2026.png
---
{{ page.authors }}

<img class="pub_teaser" src="../images/previews/Kuete3DV2026.png" alt="Teaser Image" title="teaser" />

## Abstract 

>We introduce layered Quantum Architecture Search (layered-QAS), a strategy inspired by classical network morphism that designs Parametrised Quantum Circuit (PQC) architectures by progressively growing and adapting them. PQCs offer strong expressiveness with relatively few parameters, yet they lack standard architectural layers (e.g., convolution, attention) that encode inductive biases for a given learning task. To assess the effectiveness of our method, we focus on 3D point cloud classification as a challenging yet highly structured problem. Whereas prior work on this task has used PQCs only as feature extractors for classical classifiers, our approach uses the PQC as the main building block of the classification model. Simulations show that our layered-QAS mitigates barren plateau, outperforms quantum-adapted local and evolutionary QAS baselines, and achieves state-of-the-art results among PQC-based methods on the ModelNet dataset 

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 
    @inproceedings{
      meli2026layered,
      title={Layered Quantum Architecture Search for 3D Point Cloud Classification},
      author={Natacha Kuete Meli and Jovita Lukasik and Vladislav Golyanik and Michael Moeller},
      booktitle={Thirteenth International Conference on 3D Vision},
      year={2026},
      }
