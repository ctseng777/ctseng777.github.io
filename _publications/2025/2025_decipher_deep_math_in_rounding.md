---
title: "Decipher Deep Math: Numeric Rounding Behaviors in LLMs"
authors:
- Chiung-Yi Tseng
- Maisha Thasin
- Danyang Zhang
- Blessing Effiong
- Somshubhra Roy
venue: "CoRR (arXiv preprint)"
date: 2025-01-01
arxiv: "2504.16136"
type: "preprint"
selected: false
abstract: >-
  This research investigates how language models understand and process numerical rounding tasks through linear probing techniques. We analyze the internal representations of various model architectures to understand how they encode proximity to multiples of 5 and 10. Our study implements streaming linear probes that process activations in batches rather than storing entire activation matrices, enabling memory-efficient analysis across multiple architectures including Transformer-based models (Qwen, Dream) and State Space Models (Mamba). Through layer-wise analysis, we identify which layers in different architectures best encode numerical proximity information and reveal significant differences between "thinking" and "non-thinking" model variants.
cover: /assets/images/covers/rounding.png  

links:
  Code: file:///Users/moonshine/workspace/Decipher-Deep-Math-in-Rounding/index.html
---