---
title: "Plug-and-Play Confidence-Aware Keyframe Selection for Efficient Video Understanding"
collection: publications
category: manuscripts
permalink: /publication/2026-keyframe-selection
excerpt: 'We propose a plug-and-play confidence-aware keyframe selection strategy to reduce redundant information and boost the efficiency of video understanding models.'
date: 2026-01-01
venue: 'ACM MM 2026 (Under Review)'
slidesurl: ''
paperurl: ''
bibtexurl: ''
citation: ' "Plug-and-Play Confidence-Aware Keyframe Selection for Efficient Video Understanding". <i>ACM MM 2026</i>. (Under Review)'
---

Despite the strong performance of Multi-modal Large Language Models (MLLMs) in Video Question Answering (VideoQA), accurately grounding visual evidence in long videos remains challenging. Existing methods typically perform keyframe selection uniformly across all samples based on frame–text relevance, overlooking the fact that a large portion of questions can already be correctly answered with uniformly sampled frames. In this paper, we propose Confidence-Aware Keyframe Selection(CA-KFS), a confidence-aware keyframe selection framework. For predictions obtained from uniform sampling, we directly accept high-confidence answers. For low-confidence cases, we formulate keyframe selection as an optimization problem with three key objectives: (1) distribution-weighted frame–option relevance based on the initial answer probabilities, (2) coverage over candidate options to avoid missing relevant evidence, and (3) discriminability of selected frames to reduce uncertainty. Experiments on VideoMME and LongVideoBench show that our training-free CA-KFS reduces cross-modal query retrieval of visual and text tokens by 77.3\% and 74.3\%, while improving accuracy over uniform sampling by 1.9\% and 4.9\%, respectively.
