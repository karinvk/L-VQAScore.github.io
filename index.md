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

## Attribute Confusion Problem
x

## Our Approach
The pipeline of the proposed L-VQAScore in measuring the alignment between the conditioning prompt and the generated image is shown as below. We represent the conditioning text into structured entity-attribute pairs. L-VQAScore localizes regions of interest leveraging entity categories via a semantic segmentation module. Then reflection and leakage questions are composed to evaluate the presence of desired and leaked attributes in the localized regions, accounting for both attribute depiction and localization.
![Method1](/static/image/method_1.png)
![Method2](/static/image/method_1.png)
*Figure 1: L-VQAScore methodology. *

## Key Contributions
- We investigate and validate the overlooked attribute confusion problem in T2I evaluation with a carefully designed evaluation data covering both automated metrics and human evaluation.
- We demonstrate that visual localization and attribute-centric VQA are effective strategies in addressing attribute confusion evaluation.
- We propose a new human evaluation protocol and an automated T2I evaluation method L-VQAScore, leveraging both reflection and leakage questions on localized visual content.
- L-VQAScore effectively mitigates the attribute confusion in T2I evaluation, achieving improved correlation with human annotations compared to state-of-the-art metrics.

![Performance Comparision](/static/image/results.png)
*Figure 3: Performance in T2I alignment regarding the localized study F1 Score, Precision and Recall. L-VQAScore consistently surpasses existing state-of-the-art methods.*

## Relevant Works
x

## Citation
```
x
```
