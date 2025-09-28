---
title: "When Judgment Becomes Noise: How Design Failures in LLM Judge Benchmarks Silently Undermine Validity (Under Review)"
authors:
- Benjamin Feuer
- Chiung-Yi Tseng
- Astitwa Sarthak Lathe
- Oussama Elachqar
- John P Dickerson

venue: "arXiv preprint"
date: 2025-09-24
arxiv: "2509.20293"
type: "preprint"
selected: true
#project: "https://anonymous.4open.science/r/judgment-to-noise-947D/"
cover: "/assets/images/covers/llm_judge.png"
abstract: >-
  LLM-judged benchmarks are increasingly used to evaluate complex model behaviors, yet their design introduces failure modes absent in conventional, groundtruth–based benchmarks. We argue that, without tight objectives and verifiable constructions, benchmark rankings can produce high-confidence rankings that are in fact largely noise. We introduce two mechanisms to diagnose these issues. Schematic adherence quantifies how much of a judge’s overall verdict is explained by the explicit evaluation schema, revealing unexplained variance when judges deviate from their own rubric. Psychometric validity aggregates internal consistency and discriminant validity signals to quantify irreducible uncertainty in any benchmarking run. Applying these tools to Arena-Hard Auto, we find severe schema incoherence and factor collapse across popular judges: e.g., unexplained variance exceeding 90% for DeepSeek-R1-32B and factor correlations above 0.93 for most criteria. We also show that the ELO-style aggregation used by Arena-Hard Auto collapses and masks genuine ranking uncertainty. Our results highlight design failures that undermine validity and offer actionable principles for building better-scoped, reliability-aware LLM-judged benchmarks. We release our code at  https://anonymous.4open.science/r/judgment-to-noise-947D/README.md
links:
  Code: "https://anonymous.4open.science/r/judgment-to-noise-947D/"
  Paper: "https://arxiv.org/pdf/2509.20293v1"
---
