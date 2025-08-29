---
title: "Transferrable Surrogates in Expressive Neural Architecture Search Spaces"
collection: publications
permalink: /2025-09-08-TransSurr
date: 2025-09-08
venue: 'International Conference on Automated Machine Learning'
paperurl: 'https://openreview.net/pdf?id=TEup1DJTzd'
authors: 'Shiwen Qin, Gabriela Kadlecová, Martin Pilát, Shay B. Cohen, Roman Neruda, Elliot J. Crowley, <b>Jovita Lukasik</b>, Linus Ericsson'
bibtex: true
teaser: /previews/QinAutoml2025.png
---
{{ page.authors }}

<img class="pub_teaser" src="../images/previews/QinAutoml2025.png" alt="Teaser Image" title="teaser" />

## Abstract 

Neural architecture search (NAS) faces a challenge in balancing the exploration of expressive, broad search spaces that enable architectural innovation with the need for efficient evaluation of architectures to effectively search such spaces. We investigate surrogate model training for improving search in highly expressive NAS search spaces based on context-free grammars. We show that i) surrogate models trained either using zero-cost-proxy metrics and neural graph features (GRAF) or by fine-tuning an off-the-shelf LM have high predictive power for the performance of architectures both within and across datasets, ii) these surrogates can be used to filter out bad architectures when searching on novel datasets, thereby significantly speeding up search and achieving better final performances, and iii) the surrogates can be further used directly as the search objective for huge speed-ups.


## Resources

{% if page.paperurl %}<a href=" {{ page.paperurl }} ">[pdf]</a>{% endif %} {% if page.arxiv %}<a href=" {{ page.arxiv }} ">[arxiv]</a>{% endif %} {% if page.code %}<a href=" {{ page.code }} ">[github]</a>{% endif %} {% if page.video %}<a href=" {{ page.video }} ">[video]</a>{% endif %} {% if poster %}<a href=" {{ page.poster }} ">[video]</a>{% endif %}

## Bibtex 
 
@inproceedings{
qin2025transferrable,
title={Transferrable Surrogates in Expressive Neural Architecture Search Spaces},
author={Shiwen Qin and Gabriela Kadlecov{\'a} and Martin Pil{\'a}t and Shay B Cohen and Roman Neruda and Elliot J. Crowley and Jovita Lukasik and Linus Ericsson},
booktitle={AutoML 2025 Methods Track},
year={2025},
url={https://openreview.net/forum?id=TEup1DJTzd}
}


