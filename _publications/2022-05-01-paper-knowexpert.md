---
title: "Retrieval-Free Knowledge-Grounded Dialogue Response Generation with Adapters"
collection: publications
permalink: /publication/2022-05-01-paper-knowexpert.md
excerpt: ''
date: 2022-06-01
venue: 'DialDoc Workshop in ACL 2022'
paperurl: 'https://aclanthology.org/2022.dialdoc-1.10.pdf'
authors: 'Yan Xu, Etsuko Ishii, Samuel Cahyawijaya, Zihan Liu, Genta Indra Winata, Andrea Madotto, Dan Su, Pascale Fung'
paper: 'https://aclanthology.org/2022.dialdoc-1.10.pdf'
code: 'https://github.com/HLTCHKUST/KnowExpert'
citation: 
award: 'Best Student Paper Award'
show_year: true
---
To diversify and enrich generated dialogue responses, knowledge-grounded dialogue has been investigated in recent years. The existing methods tackle the knowledge grounding challenge by retrieving the relevant sentences over a large corpus and augmenting the dialogues with explicit extra information. Despite their success, however, the existing works have drawbacks on the inference efficiency. This paper proposes KnowExpert, an end-to-end framework to bypass the explicit retrieval process and inject knowledge into the pre-trained language models with lightweight adapters and adapt to the knowledge-grounded dialogue task. To the best of our knowledge, this is the first attempt to tackle this challenge without retrieval in this task under an open-domain chit-chat scenario. The experimental results show that KnowExpert performs comparably with some retrieval-based baselines while being time-efficient in inference, demonstrating the effectiveness of our proposed method.