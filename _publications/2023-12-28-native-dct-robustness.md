---
title: "Improving Native CNN Robustness with Filter Frequency Regularization"
collection: publications
permalink: /publication/2023-12-28-native-dct-robustness
date: 2023-12-28
venue: 'Transactions on Machine Learning Research'
paperurl: 'https://openreview.net/forum?id=2wecNCpZ7Y'
authors: '<b>Jovita Lukasik</b>, Paul Gavrikov, Janis Keuper, Margret Keuper'
bibtex: true
teaser: /previews/LukasikTMLR2023.png
code: https://github.com/jovitalukasik/filter_freq_reg
---

{{ page.authors }}

<img class="pub_teaser" src="../images/previews/LukasikTMLR2023.png" alt="Teaser Image" title="teaser" />

## Abstract 

> Neural networks tend to overfit the training distribution and perform poorly on out-of-distribution data. A conceptually simple solution lies in adversarial training, which introduces worst-case perturbations into the training data and thus improves model generalization to some extent. However, it is only one ingredient towards generally more robust models and requires knowledge about the potential attacks or inference time data corruptions during model training. This paper focuses on the native robustness of models that can learn robust behavior directly from conventional training data without out-of-distribution examples. To this end, we study the frequencies in learned convolution filters. Clean-trained models often prioritize high-frequency information, whereas adversarial training enforces models to shift the focus to low-frequency details during training. By mimicking this behavior through frequency regularization in learned convolution weights, we achieve improved native robustness to adversarial attacks, common corruptions, and other out-of-distribution tests. Additionally, this method leads to more favorable shifts in decision-making towards low-frequency information, such as shapes, which inherently aligns more closely with human vision.


## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 

      @article{lukasik2023improving,
	title={Improving Native {CNN} Robustness with Filter Frequency Regularization},
	author={Jovita Lukasik and Paul Gavrikov and Janis Keuper and Margret Keuper},
	journal={Transactions on Machine Learning Research},
	issn={2835-8856},
	year={2023}}



