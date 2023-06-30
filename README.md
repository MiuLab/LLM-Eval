# LLM-EVAL: Unified Multi-Dimensional Automatic Evaluation for Open-Domain Conversations with Large Language Models

This repo contains the code for the paper "LLM-EVAL: Unified Multi-Dimensional Automatic Evaluation for Open-Domain Conversations with Large Language Models" by Yen-Ting Lin and Yun-Nung Chen.

## Abstract
We propose LLM-EVAL, a unified multi-dimensional automatic evaluation method for open-domain conversations with large language models (LLMs). Existing evaluation methods often rely on human annotations, ground-truth responses, or multiple LLM prompts, which can be expensive and time-consuming. To address these issues, we design a single prompt-based evaluation method that leverages a unified evaluation schema to cover multiple dimensions of conversation quality in a single model call. We extensively evaluate the performance of LLM-EVAL on various benchmark datasets, demonstrating its effectiveness, efficiency, and adaptability compared to state-of-the-art evaluation methods. Our analysis also highlights the importance of choosing suitable LLMs and decoding strategies for accurate evaluation results. LLM-EVAL offers a versatile and robust solution for evaluating open-domain conversation systems, streamlining the evaluation process and providing consistent performance across diverse scenarios.

## Usage
See llm_eval.py

## Citation
If you use LLM-EVAL in your work, please cite:

```
@article{DBLP:journals/corr/abs-2305-13711,
  author       = {Yen{-}Ting Lin and
                  Yun{-}Nung Chen},
  title        = {LLM-Eval: Unified Multi-Dimensional Automatic Evaluation for Open-Domain
                  Conversations with Large Language Models},
  journal      = {CoRR},
  volume       = {abs/2305.13711},
  year         = {2023},
  url          = {https://doi.org/10.48550/arXiv.2305.13711},
  doi          = {10.48550/arXiv.2305.13711},
  eprinttype    = {arXiv},
  eprint       = {2305.13711},
  timestamp    = {Mon, 05 Jun 2023 15:42:15 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2305-13711.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```
