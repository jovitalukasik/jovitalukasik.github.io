---
title: "Implicit Representations for Image Segmentation"
collection: publications
permalink: /publication/2023-12-15-convex-img-seg
date: 2023-12-15
venue: 'Unireps@NeurIPS 2023'
paperurl: 'https://openreview.net/forum?id=LSSiDy7fG1'
authors: 'Jan Philipp Schneider, Mishal Fatima, <b>Jovita Lukasik</b>, Andreas Kolb, Margret Keuper, Michael Moeller'
bibtex: true
teaser: /previews/SchneiderUnireps2023.png
---
{{ page.authors }}

<img class="pub_teaser" src="../images/previews/SchneiderUnireps2023.png" alt="Teaser Image" title="teaser" />

## Abstract 

> Image segmentation has greatly advanced over the past ten years. Yet, even the most recent techniques face difficulties producing good results in challenging situations, e.g., if training data are scarce, out-of-distribution examples need to be segmented, or if objects are occluded. In such situations, the inclusion of (geometric) constraints can improve the segmentation quality significantly. In this paper, we study the constraint of the segmented region being segmented convex. Unlike prior work that encourages such a property with computationally expensive penalties on segmentation masks represented explicitly on a grid of pixels, our work is the first to consider an implicit representation. Specifically, we represent the segmentation as a parameterized function that maps spatial coordinates to the likeliness of a pixel belonging to the fore- or background. This enables us to provably ensure the convexity of the segmented regions with the help of input convex neural networks. Numerical experiments demonstrate how to encourage explicit and implicit representations to match in order to benefit from the convexity constraints in several challenging segmentation scenarios.


## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 

      @inproceedings{
	schneider2023implicit,
	title={Implicit Representations for Image Segmentation},
	author={Jan Philipp Schneider and Mishal Fatima and Jovita Lukasik and Andreas Kolb and Margret Keuper and Michael Moeller},
	booktitle={UniReps:  the First Workshop on Unifying Representations in Neural Models},
	year={2023}}



