---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
feature_row:
  - image_path: projects/fast-diffusion-attention.png
    alt: "The block diffusion attention mask"
    title: "Fast Diffusion Attention"
    excerpt: |
      **Yuezhou Hu**, Kurt Keutzer, Chenfeng Xu

      Block diffusion training at FlashAttention speed: attention kernels with the block diffusion mask built into
      FlashAttention-3 on Hopper and FlashAttention-2 on Ampere and Ada. A training step runs at 0.96-1.10x the
      throughput of FlashAttention-3 doing the same work.

      [[Code]](https://github.com/yuezhouhu/fast-diffusion-attention)
    url: "/projects/fast-diffusion-attention/"
    btn_label: "Project page"
    btn_class: "btn--info"
  - image_path: projects/residual-context-diffusion.png
    alt: "Residual denoising in Residual Context Diffusion"
    title: "Residual Context Diffusion"
    excerpt: |
      **Yuezhou Hu**\*, Harman Singh\*, Monishwaran Maheswaran\*, et al. · ICML 2026

      Diffusion LLMs discard the predictions of the tokens they remask at every denoising step. RCD turns them into
      contextual residuals for the next step: it improves accuracy by 4–11 percentage points, nearly doubles accuracy
      on AIME, and reaches the baseline's peak accuracy with up to 4–5x fewer denoising steps.

      [[arXiv]](https://arxiv.org/abs/2601.22954) [[Code]](https://github.com/yuezhouhu/residual-context-diffusion) [[Models]](https://huggingface.co/collections/yuezhouhu/residual-context-diffusion)
    url: "/projects/residual-context-diffusion/"
    btn_label: "Project page"
    btn_class: "btn--info"
---

{% include feature_row type="left" %}
