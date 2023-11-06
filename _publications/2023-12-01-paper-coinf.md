---
title: "Contrastive Learning for Inference in Dialogue"
collection: publications
permalink: /publication/2023-12-01-paper-coinf.md
excerpt: ''
date: 2023-12-01
venue: 'EMNLP 2023 Main'
paperurl: 'https://arxiv.org/pdf/2310.12467.pdf'
authors: 'Etsuko Ishii, Yan Xu, Bryan Wilie, Ziwei Ji, Holy Lovenia, Willy Chung, Pascale Fung'
paper: 'https://arxiv.org/pdf/2310.12467.pdf'
code: 'https://github.com/HLTCHKUST/contrastive_inference_dialogue'
citation: 
---
Inference, especially those derived from inductive processes, is a crucial component in our conversation to complement the information implicitly or explicitly conveyed by a speaker. While recent large language models show remarkable advances in inference tasks, their performance in inductive reasoning, where not all information is present in the context, is far behind deductive reasoning. In this paper, we analyze the behavior of the models based on the task difficulty defined by the semantic information gap -- which distinguishes inductive and deductive reasoning (Johnson-Laird, 1988, 1993). Our analysis reveals that the disparity in information between dialogue contexts and desired inferences poses a significant challenge to the inductive inference process. To mitigate this information gap, we investigate a contrastive learning approach by feeding negative samples. Our experiments suggest negative samples help models understand what is wrong and improve their inference generations.