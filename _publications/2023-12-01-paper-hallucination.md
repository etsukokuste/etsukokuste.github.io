---
title: "Towards Mitigating Hallucination in Large Language Models via Self-Reflection"
collection: publications
permalink: /publication/2023-12-01-paper-hallucination.md
excerpt: ''
date: 2023-12-01
venue: 'EMNLP 2023 Findings'
paperurl: 'https://arxiv.org/pdf/2310.06271.pdf'
authors: 'Ziwei Ji, Tiezheng Yu, Yan Xu, Nayeon Lee, Etsuko Ishii, Pascale Fung'
paper: 'https://arxiv.org/pdf/2310.06271.pdf'
code: 'https://github.com/ziweiji/Self_Reflection_Medical'
citation: 
show_year: true
---
Large language models (LLMs) have shown promise for generative and knowledge-intensive tasks including question-answering (QA) tasks. However, the practical deployment still faces challenges, notably the issue of "hallucination", where models generate plausible-sounding but unfaithful or nonsensical information. This issue becomes particularly critical in the medical domain due to the uncommon professional concepts and potential social risks involved. This paper analyses the phenomenon of hallucination in medical generative QA systems using widely adopted LLMs and datasets. Our investigation centers on the identification and comprehension of common problematic answers, with a specific emphasis on hallucination. To tackle this challenge, we present an interactive self-reflection methodology that incorporates knowledge acquisition and answer generation. Through this feedback process, our approach steadily enhances the factuality, consistency, and entailment of the generated answers. Consequently, we harness the interactivity and multitasking ability of LLMs and produce progressively more precise and accurate answers. Experimental results on both automatic and human evaluation demonstrate the superiority of our approach in hallucination reduction compared to baselines.