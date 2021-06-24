---
title: "Model Generalization on COVID-19 Fake News Detection"
collection: publications
permalink: /publication/2021-01-01-paper-constraint.md
excerpt: ''
date: 2021-01-01
venue: 'CONSTRAINT 2021 Workshop in AAAI'
paperurl: 'https://arxiv.org/abs/2101.03841'
authors: 'Yejin Bang, Etsuko Ishii, Samuel Cahyawijaya, Ziwei Ji, Pascale Fung'
paper: 'https://arxiv.org/pdf/2101.03841.pdf'
code: 
citation: 
show_year: true
---
Amid the pandemic COVID-19, the world is facing unprecedented infodemic with the proliferation of both fake and real information. Considering the problematic consequences that the COVID-19 fake-news have brought, the scientific community has put effort to tackle it. To contribute to this fight against the infodemic, we aim to achieve a robust model for the COVID-19 fake-news detection task proposed at CONSTRAINT 2021 (FakeNews-19) by taking two separate approaches: 1) fine-tuning transformers based language models with robust loss functions and 2) removing harmful training instances through influence calculation. We further evaluate the robustness of our models by evaluating on different COVID-19 misinformation test set (Tweets-19) to understand model generalization ability. With the first approach, we achieve 98.13% for weighted F1 score (W-F1) for the shared task, whereas 38.18% W-F1 on the Tweets-19 highest. On the contrary, by performing influence data cleansing, our model with 99% cleansing percentage can achieve 54.33% W-F1 score on Tweets-19 with a trade-off. By evaluating our models on two COVID-19 fake-news test sets, we suggest the importance of model generalization ability in this task to step forward to tackle the COVID-19 fake-news problem in online social media platforms.