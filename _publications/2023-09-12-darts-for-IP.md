---
title: "Differentiable Architecture Search: a One-Shot Method?"
collection: publications
permalink: /publication/2023-09-12-darts-for-IP
date: 2023-09-12
venue: 'AutoML Conference 2023 Workshops'
paperurl: 'https://openreview.net/forum?id=LV-5kHj-uV5'
authors: '<b>Jovita Lukasik</b>, Jonas Geiping, Michael Moeller, Margret Keuper'
bibtex: true
teaser: /previews/LukasikAutoML2023.png
---
{{ page.authors }}

<img class="pub_teaser" src="../images/previews/LukasikAutoML2023.png" alt="Teaser Image" title="teaser" />

## Abstract 

> Differentiable architecture search (DAS) is a widely researched tool for the design of novel architectures. The main benefit of DAS is the effectiveness achieved through the weight-sharing one-shot paradigm, which allows efficient architecture search. In this work, we investigate DAS in a systematic case study of inverse problems, which allows us to analyze these potential benefits in a controlled manner. We demonstrate that the success of DAS can be extended from image classification to signal reconstruction, in principle. However, our experiments also expose three fundamental difficulties in the evaluation of DAS-based methods in inverse problems: First, the results show a large variance in all test cases. Second, the final performance is strongly dependent on the hyperparameters of the optimizer. And third, the performance of the weight-sharing architecture used during training does not reflect the final performance of the found architecture well. While the results on image reconstruction confirm the potential of the DAS paradigm, they challenge the common understanding of DAS as a one-shot method.
## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 

      @inproceedings{lukasik2023differentiable,
	title={Differentiable Architecture Search: a One-Shot Method?},
	author={Jovita Lukasik and Jonas Geiping and Michael Moeller and Margret Keuper},
	booktitle={AutoML Conference 2023},
	year={2023}}



