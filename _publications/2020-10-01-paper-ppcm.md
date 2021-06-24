---
title: "Plug-and-Play Conversational Models"
collection: publications
permalink: /publication/2020-10-01-paper-lrec.md
excerpt: ''
date: 2020-10-01
venue: 'EMNLP 2020 Findings'
paperurl: 'https://www.aclweb.org/anthology/2020.findings-emnlp.219'
authors: 'Andrea Madotto, Etsuko Ishii, Zhaojiang Lin, Sumanth Dathathri, Pascale Fung'
paper: 'https://www.aclweb.org/anthology/2020.findings-emnlp.219.pdf'
code: 'https://github.com/andreamad8/PPCM'
citation: 
show_year: true
---
There has been considerable progress made towards conversational models that generate coherent and fluent responses; however, this often involves training large language models on large dialogue datasets, such as Reddit. These large conversational models provide little control over the generated responses, and this control is further limited in the absence of annotated conversational datasets for attribute specific generation that can be used for fine-tuning the model. In this paper, we first propose and evaluate plug-and-play methods for controllable response generation, which does not require dialogue specific datasets and does not rely on fine-tuning a large model. While effective, the decoding procedure induces considerable computational overhead, rendering the conversational model unsuitable for interactive usage. To overcome this, we introduce an approach that does not require further computation at decoding time, while also does not require any fine-tuning of a large language model. We demonstrate, through extensive automatic and human evaluation, a high degree of control over the generated conversational responses with regard to multiple desired attributes, while being fluent.