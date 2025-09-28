---
title: "StreetMath: Study of LLMs’ Approximation Behaviors (Under Review)"
authors:
- 
date: 2025-09-26
type: "preprint"
selected: true
project: "https://anonymous.4open.science/r/StreetMath-1/"
cover: "/assets/images/covers/street_math.png"
abstract: >-
  There is a substantial body of literature examining the mathematical reasoning capabilities of large language models (LLMs); particularly their performance on precise arithmetic operations in autoregressive architectures. However, their ability to perform approximate reasoning in informal fast-paced mathematical operations has received far less attention, especially among non-transformer models. Our work addresses this gap by introducing StreetMath, a benchmark designed to evaluate models’ approximation abilities under real-world approximation scenarios. We conduct extensive evaluations across different LLM architectures: Qwen3-4B-Instruct-2507, Qwen3-4B-Thinking-2507, Dream-v0-Instruct-7B, Falcon-Mamba-7B-Instruct and mamba-GPT-3B. Furthermore, we apply mechanistic interpretability techniques to probe their internal computational states. Our analysis reveals that LLMs generally attempt to compute exact values or invoke external tools even in tasks that call for approximation. Moreover, while models sometimes reach the correct answer in early layers or steps, they still consume more tokens when solving approximation tasks. Additional experiments indicate that exact and approximate arithmetic operations rely on largely separate neural components. These findings suggest that LLMs’ limited performance in approximation scenarios may stem from training corpora that predominantly emphasize exact arithmetic. Drawing upon research on cognitive psychology, we argue that LLMs do not exhibit cognitive miserliness in the same way humans do in street math settings. We open source our work https://anonymous.4open.science/r/StreetMath-1/

links:
  Code: "https://anonymous.4open.science/r/StreetMath-1/"
  Paper: "https://openreview.net/pdf?id=gU20Mpzm0y"
---
