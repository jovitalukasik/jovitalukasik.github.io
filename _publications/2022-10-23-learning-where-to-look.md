---
title: "Learning Where to Look – Generative NAS Is Surprisingly Efficient"
collection: publications
permalink: /publication/2022-10-23-learning-where-to-look
date: 2022-10-23
venue: 'European Conference on Computer Vision'
paperurl: 'https://www.ecva.net/papers/eccv_2022/papers_ECCV/html/6011_ECCV_2022_paper.php'
authors: '<b>Jovita Lukasik</b>, Steffen Jung, Margret Keuper'
arxiv: 'https://arxiv.org/abs/2203.08734'
bibtex: true
teaser: /previews/LukasikECCV2022.pdf
code: http://github.com/jovitalukasik/AG-Net
---
{{ page.authors }}

<img class="pub_teaser" src="../images/previews/LukasikECCV2022.pdf" alt="Teaser Image" title="teaser" />

## Abstract 

>The efficient, automated search for well-performing neural architectures (NAS) has drawn increasing attention in the recent past. Thereby, the predominant research objective is to reduce the necessity of costly evaluations of neural architectures while efficiently exploring large search spaces. To this aim, surrogate models embed architectures in a latent space and predict their performance, while generative models for neural architectures enable optimization-based search within the latent space the generator draws from. Both, surrogate and generative models, have the aim of facilitating query-efficient search in a well-structured latent space. In this paper, we further improve the trade-off between query-efficiency and promising architecture generation by leveraging advantages from both, efficient surrogate models and generative design. To this end, we propose a generative model, paired with a surrogate predictor, that iteratively learns to generate samples from increasingly promising latent subspaces. This approach leads to very effective and efficient architecture search, while keeping the query amount low. In addition, our approach allows in a straightforward manner to jointly optimize for multiple objectives such as accuracy and hardware latency. We show the benefit of this approach not only w.r.t. the optimization of architectures for highest classification accuracy but also in the context of hardware constraints and outperform state-of-the-art methods on several NAS benchmarks for single and multiple objectives. We also achieve state-of-the-art performance on ImageNet. The code is available at https://github.com/jovitalukasik/AG-Net.

## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 

      @inproceedings{Lukasik2022agnet,
	author={Lukasik, Jovita and Jung, Steffen and Keuper, Margret},
	title={Learning Where to Look -- Generative NAS is Surprisingly Efficient},
	booktitle={European Conference on Computer Vision},
	year={2022}}



