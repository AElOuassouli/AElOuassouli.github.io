---
title: "Attention Is All You Need"
author: "Vaswani et al."
category: articles
tags:
  - machine learning
  - deep learning
  - transformers
date: 2024-03-01
rating: 5
collection: reading
permalink: /reading/attention-is-all-you-need/
excerpt: "The paper that introduced the Transformer architecture, now the backbone of virtually all large language models. A landmark work in deep learning."
---

**Authors:** Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, Illia Polosukhin  
**Venue:** NeurIPS 2017  
**Type:** Paper  
**Rating:** ★★★★★

## Summary

The paper proposes the Transformer, a model architecture based entirely on attention mechanisms, dispensing with recurrence and convolutions. The self-attention mechanism allows the model to relate positions in a sequence regardless of their distance.

## What I Found Interesting

The elegance of replacing sequential RNN processing with parallel attention computation was remarkable. The multi-head attention mechanism allows the model to jointly attend to information from different representation subspaces.

## Key Takeaways

- Self-attention scales better than recurrent models for long sequences.
- Positional encodings are a simple yet effective trick for injecting sequence order.
- The architecture generalizes well beyond machine translation.
