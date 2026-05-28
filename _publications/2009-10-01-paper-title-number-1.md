---
title: "Boundary Detection over Frame Captioning: A Key to Efficient Long Video Chaptering"
collection: publications
category: manuscripts
permalink: /publication/2025-acmmm-boundary-detection
excerpt: 'This work focuses on long video chaptering, and proposes a novel framework combining frame captioning and boundary detection to achieve efficient long video understanding.'
date: 2026-01-01
venue: 'ACM MM 2026 (Under Review)'
slidesurl: ''
paperurl: ''
bibtexurl: ''
citation: '"Boundary Detection over Frame Captioning: A Key to Efficient Long Video Chaptering". <i>ACM MM 2026</i>. (Under Review)'
---

<center>
<img src="/images/acmmm26_cbd_llm.png" width="800">
</center>
<p align="center">Figure 1: The overall framework of our CBD-LLM.</p>

Long-form video chaptering enables efficient navigation and retrieval by segmenting videos into semantically coherent chapters with timestamps and titles. Existing pipelines often rely on frame captioning and speech information to guide large language models (LLMs), resulting in high inference latency and redundant information, while providing marginal benefit for many videos. Observing that accurate boundary localization often matters more than exhaustive content description, we propose Chapter Boundary Detection for LLM-based video chaptering (CBD-LLM), a boundary-centric framework for long-form video chaptering. Our method first generates candidate temporal boundaries via lightweight visual–speech alignment and shot analysis, then filters them using a trainable binary classifier trained on ground-truth chapters. The selected optimal boundaries are incorporated as structural cues into our LLM, adapted via LoRA, eliminating the need for dense frame captions. Experiments on the VidChapters-7M dataset show that CBD-LLM achieves state-of-the-art performance (eg. 104.5 vs 100.9 CIDEr score) while reducing computational overhead by 50\% (30.2 s → 15.1 s), demonstrating a better trade-off between speed and accuracy and highlighting the advantage of boundary-aware design in multimodal video understanding.
