---
title: "Improving Native CNN Robustness with Filter Frequency Regularization"
collection: publications
permalink: /publication/2024-07-21-constrained-seg
date: 2024-07-21
venue: 'Proceedings of the 41st International Conference on Machine Learning'
paperurl: 'https://proceedings.mlr.press/v235/schneider24a.html'
authors: 'Jan Philipp Schneider, Mishal Fatima, <b>Jovita Lukasik</b>, Andreas Kolb, Margret Keuper, Michael Moeller'
bibtex: true
teaser: /previews/SchneiderICML2024.png
code: https://github.com/jp-schneider/awesome
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/SchneiderICML2024.png" alt="Teaser Image" title="teaser" />

## Abstract 

> Implicit representations allow to use a parametric function that maps (spatial) coordinates to the value that is traditionally stored in each pixel, e.g. RGB values, instead of a discrete grid. This has recently proven quite advantageous as an internal representation for images or scenes for deep learning models. Yet, its potential to ensure certain properties of the solution has not yet been fully explored. In this work, we demonstrate that implicit representations are a powerful tool for enforcing a variety of different geometric constraints in image segmentation. While convexity, star-shape, path-connectedness, periodicity, or symmetry of the (spatial or space-time) region to be segmented are very challenging to enforce for pixel-wise discretizations, a suitable parametrization of an implicit representation, mapping spatial or spatio-temporal coordinates to the likeliness of a pixel belonging to the fore- or background, allows to provably ensure such constraints. Several numerical examples demonstrate that challenging segmentation scenarios can benefit from the inclusion of application-specific constraints, e.g. when occlusions prevent a faithful segmentation with classical approaches.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 
	     
	@InProceedings{schneider24a,
	  title = 	 {Implicit Representations for Constrained Image Segmentation},
	  author =       {Schneider, Jan Philipp and Fatima, Mishal and Lukasik, Jovita and Kolb, Andreas and Keuper, Margret and Moeller, Michael},
	  booktitle = 	 {Proceedings of the 41st International Conference on Machine Learning},
	  year = 	 {2024}}



