---
title: Reformatted Alignment
authors:
- Run-Ze Fan
- Xuefeng Li
- Haoyang Zou
- Junlong Li
- Shwai He
- Ethan Chern
- admin
- Pengfei Liu
date: '2024-02-19'
publishDate: '2024-11-25T19:10:00.436144Z'
publication_types:
- paper-conference
publication: '*Findings of EMNLP 2024*'
abstract: The quality of finetuning data is crucial for aligning large language models
  (LLMs) with human values. Current methods to improve data quality are either labor-intensive
  or prone to factual errors caused by LLM hallucinations. This paper explores elevating
  the quality of existing instruction data to better align with human values, introducing
  a simple and effective approach named ReAlign, which reformats the responses of
  instruction data into a format that better aligns with pre-established criteria
  and the collated evidence. This approach minimizes human annotation, hallucination,
  and the difficulty in scaling, remaining orthogonal to existing alignment techniques.
  Experimentally, ReAlign significantly boosts the general alignment ability, math
  reasoning, factuality, and readability of the LLMs.Encouragingly, without introducing
  any additional data or advanced training techniques, and merely by reformatting
  the response, LLaMA-2-13B′s mathematical reasoning ability on GSM8K can be improved
  **from 46.77% to 56.63%** in accuracy. Additionally, a mere 5% of ReAlign data yields
  a 67% boost in general alignment ability measured by the Alpaca dataset. This work
  highlights the need for further research into the science and mechanistic interpretability
  of LLMs. We have made the associated code and data publicly accessible to support
  future studies at https://github.com/GAIR-NLP/ReAlign.
links:
- name: URL
  url: https://gair-nlp.github.io/ReAlign/
url_pdf: 'https://arxiv.org/abs/2402.12219'
url_code: 'https://github.com/GAIR-NLP/ReAlign'
---
