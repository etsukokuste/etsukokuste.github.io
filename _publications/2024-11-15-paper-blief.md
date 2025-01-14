---
title: "Towards Mitigating Hallucination in Large Language Models via Self-Reflection"
collection: publications
permalink: /publication/2024-11-15-paper-blief.md
excerpt: ''
date: 2024-11-15
venue: 'EMNLP 2024'
paperurl: 'https://arxiv.org/pdf/2406.19764'
authors: 'Bryan Wilie, Samuel Cahyawijaya, Etsuko Ishii, Junxian He, Pascale Fung'
paper: 'https://arxiv.org/pdf/2406.19764'
code: 'https://github.com/HLTCHKUST/belief-revision'
citation: 
show_year: true
---
The capability to reason from text is crucial for real-world NLP applications. Real-world scenarios often involve incomplete or evolving data. In response, individuals update their beliefs and understandings accordingly. However, most existing evaluations assume that language models (LMs) operate with consistent information. We introduce Belief-R, a new dataset designed to test LMs' belief revision ability when presented with new evidence. Inspired by how humans suppress prior inferences, this task assesses LMs within the newly proposed delta reasoning (ΔR) framework. Belief-R features sequences of premises designed to simulate scenarios where additional information could necessitate prior conclusions drawn by LMs. We evaluate ∼30 LMs across diverse prompting strategies and found that LMs generally struggle to appropriately revise their beliefs in response to new information. Further, models adept at updating often underperformed in scenarios without necessary updates, highlighting a critical trade-off. These insights underscore the importance of improving LMs' adaptiveness to changing information, a step toward more reliable AI systems.