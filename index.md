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

## Key Contributions
- We focus on localized sketch-text image generation, advancing state-of-the-art conditioning with localized sketches and a single global text. 
- We introduce a novel method, LOTS, to mitigate attribute confusion by modularized attention-based processing per sketch-text pair, and deferring the multi-conditioning merge to the denoising process.
- We introduce a new dataset, Sketchy, in the fashion domain, to facilitate model training and evaluation for the localized text-sketch image generation problem.
- LOTS achieves state-of-the-art performance in image quality, sketch-text conditioning and attribute localization, as measured with both metrics and human evaluation.

![Performance Comparision](/static/image/performance.png)

*Figure 1: Performance Comparision between different generative models.*

## Relevant Works
x

## Citation
```
x
```
