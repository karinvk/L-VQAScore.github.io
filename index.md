---
layout: project_page
permalink: /

title: Evaluating Attribute Confusion in Fashion Text-to-Image Generation
authors:
    x
affiliations:
    x
paper: x
video: x
code: x
data: x
---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Despite the rapid advances in Text-to-Image (T2I) generation models, their evaluation remains challenging in domains like fashion, involving complex compositional generation.
Recent automated T2I evaluation methods leverage pre-trained vision-language models to measure cross-modal alignment. However, our preliminary study reveals that they are still limited in assessing rich entity-attribute semantics, facing challenges in attribute confusion, i.e., when attributes are correctly depicted but associated to the wrong entities. To address this, we build on a Visual Question Answering (VQA) localization strategy targeting one single entity at a time across both visual and textual modalities. We propose a localized human evaluation protocol and introduce a novel automatic metric, Localized VQAScore (L-VQAScore), that combines visual localization with VQA probing both correct (reflection) and miss-localized (leakage) attribute generation. 
On a newly curated dataset featuring challenging compositional alignment scenarios, L-VQAScore outperforms state-of-the-art T2I evaluation methods in terms of correlation with human judgments, demonstrating its strength in capturing fine-grained entity-attribute associations. We believe L-VQAScore can be a reliable and scalable alternative to subjective evaluations.
        </div>
    </div>
</div>

---

## Background 
x
![Background](/static/image/backgrounds.png)
*Figure 1: Fundamental difference between previous methods and our approach.*

## Our Method
x
![Method](/static/image/methods.jpeg)
*Figure 2: LOTS methodology.*

## Our Contributions
x

![Performance Comparision](/static/image/results.jpeg)
*Figure 3: Comparision between different T2I generative models.*

## Relevant Works
x

## Citation
```
x
```
