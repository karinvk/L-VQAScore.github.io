---
layout: project_page
permalink: /

title: LOTS of Fashion! Multi-Conditioning for Image Generation via Sketch-Text Pairing
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
Fashion design is a complex creative process that blends visual and textual expressions. Designers convey ideas through sketches, which define spatial structure and design elements, and textual descriptions, capturing material, texture, and stylistic details.
In this paper, we present LOcalized Text and Sketch for fashion image generation (LOTS), an approach for compositional sketch-text based generation of complete fashion outlooks. LOTS leverages a global description with paired localized sketch + text information for conditioning and introduces a novel step-based merging strategy for diffusion adaptation. 
First, a Modularized Pair-Centric representation encodes sketches and text into a shared latent space while preserving independent localized features; then, a Diffusion Pair Guidance phase integrates both local and global conditioning via attention-based guidance within the diffusion model’s multi-step denoising process. 
To validate our method, we build on Fashionpedia to release Sketchy, the first fashion dataset where multiple text-sketch pairs are provided per image. Quantitative results show LOTS achieves state-of-the-art image generation performance on both global and localized metrics, while qualitative examples and a human evaluation study highlight its unprecedented level of design customization.
        </div>
    </div>
</div>

---

## Background 
x

## Our Method
We propose LOTS, a novel approach leveraging multiple localized sketch-text pairs for image conditioning. First, the \textit{Modularized Pair-Centric Representation} module independently encodes sketches and text into a shared latent space, preserving localized features while limiting information leakage between pairs to reduce attribute confusion. Then, the \textit{Pair-former} merges text and sketch information within each pair ensuring spatially grounded descriptions that capture single-item attributes through the structural guidance of sketches.
Next, during the \textit{Diffusion Pair Guidance} phase, these localized representations serve as conditioning inputs to a pre-trained diffusion model, alongside a global textual representation specifying general appearance properties (style, background). Unlike prior methods that merge conditioning inputs upfront, our approach defers this operation to the diffusion process itself, breaking down the task across multiple denoising steps via a cross-attention strategy. 
![Method](/static/image/method.jpeg)


## Our Contributions
- We focus on localized sketch-text image generation, advancing state-of-the-art conditioning with localized sketches and a single global text. 
- We introduce a novel method, LOTS, to mitigate attribute confusion by modularized attention-based processing per sketch-text pair, and deferring the multi-conditioning merge to the denoising process.
- We introduce a new dataset, Sketchy, in the fashion domain, to facilitate model training and evaluation for the localized text-sketch image generation problem.
- LOTS achieves state-of-the-art performance in image quality, sketch-text conditioning and attribute localization, as measured with both metrics and human evaluation.

![Performance Comparision](/static/image/performance.jpeg)
*Figure 1: Performance Comparision between different T2I generative models.*

## Relevant Works
x

## Citation
```
x
```
