---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<div class="project-card">
  <a class="project-card__image" href="/projects/fast-diffusion-attention/"><img src="/projects/fast-diffusion-attention/pattern.png" alt="The block diffusion attention mask"></a>
  <div class="project-card__body">
    <h2 class="project-card__title"><a href="/projects/fast-diffusion-attention/">Fast Diffusion Attention</a></h2>
    <p class="project-card__subtitle">Block diffusion training at FlashAttention speed</p>
    <p class="project-card__meta"><strong>Yuezhou Hu</strong>, Kurt Keutzer, Chenfeng Xu</p>
    <p>Attention kernels for training block diffusion language models. The block diffusion mask is built into FlashAttention-3 on Hopper and FlashAttention-2 on Ampere and Ada: only the visible quarter of the attention matrix is computed, and a training step runs at 0.96-1.10x the throughput of FlashAttention-3 doing the same work.</p>
    <p><a href="/projects/fast-diffusion-attention/">[Project page]</a> <a href="https://github.com/yuezhouhu/fast-diffusion-attention">[Code]</a></p>
  </div>
</div>

<div class="project-card">
  <a class="project-card__image" href="/projects/residual-context-diffusion/"><img src="/projects/residual-context-diffusion/main_figure_1_0126.png" alt="Residual denoising in Residual Context Diffusion"></a>
  <div class="project-card__body">
    <h2 class="project-card__title"><a href="/projects/residual-context-diffusion/">Residual Context Diffusion</a></h2>
    <p class="project-card__subtitle">Unleashing the Potential of Diffusion LLMs via Residual Denoising</p>
    <p class="project-card__meta"><strong>Yuezhou Hu</strong>*, Harman Singh*, Monishwaran Maheswaran*, et al. · ICML 2026</p>
    <p>Diffusion LLMs discard the predictions of the tokens they remask at every denoising step. RCD turns these discarded predictions into contextual residuals for the next step: it improves accuracy by 4–11 percentage points, nearly doubles accuracy on AIME, and reaches the baseline's peak accuracy with up to 4–5x fewer denoising steps.</p>
    <p><a href="/projects/residual-context-diffusion/">[Project page]</a> <a href="https://arxiv.org/abs/2601.22954">[arXiv]</a> <a href="https://github.com/yuezhouhu/residual-context-diffusion">[Code]</a> <a href="https://huggingface.co/collections/yuezhouhu/residual-context-diffusion">[Models]</a></p>
  </div>
</div>
