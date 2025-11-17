# TAMA: Human–AI Collaborative Thematic Analysis using Multi-Agent LLMs

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![LLM](https://img.shields.io/badge/LLM-GPT--4o-black.svg)
![Status](https://img.shields.io/badge/ACM%20Computing%20for%20Healthcare-2025-blue.svg)

## Overview

TAMA is a human–AI collaborative framework for inductive thematic analysis of long, qualitative clinical interview transcripts. It uses a structured multi-agent workflow—Generation, Evaluation, and Refinement agents—combined with clinician-defined criteria to produce accurate, distinct, and clinically relevant themes. The framework reduces manual coding times by more than 99% while improving thematic coverage, distinctiveness, and alignment with expert-generated themes. TAMA was evaluated on de-identified interviews from parents of children with congenital heart disease and outperformed single-agent LLM baselines across multiple quantitative metrics.

## Key Features

- Multi-agent LLM architecture with coordinated Generation, Evaluation, and Refinement agents.
- Human-in-the-loop design with clinician-defined goals, evaluation criteria, and final approval.
- Quantitative evaluation using Jaccard similarity, hit rate, and embedding-based cosine similarity.
- End-to-end thematic analysis completed in under ten minutes, reducing manual workload by more than 99%.

## Architecture

The TAMA framework uses a multi-agent workflow consisting of Generation, Evaluation, and Refinement agents, with iterative oversight from a clinical expert. The expert provides initial goals and evaluation criteria and makes the final decision to accept or revise the generated themes.

### Workflow Diagram
![TAMA Architecture](figures/tama_architecture.png)

## Citation

If you use TAMA in your research, please cite:

```bibtex
@misc{xu2025tamahumanaicollaborativethematic,
      title={TAMA: A Human-AI Collaborative Thematic Analysis Framework Using Multi-Agent LLMs for Clinical Interviews}, 
      author={Huimin Xu and Seungjun Yi and Terence Lim and Jiawei Xu and Andrew Well and Carlos Mery and Aidong Zhang and Yuji Zhang and Heng Ji and Keshav Pingali and Yan Leng and Ying Ding},
      year={2025},
      eprint={2503.20666},
      archivePrefix={arXiv},
      primaryClass={cs.HC},
      url={https://arxiv.org/abs/2503.20666}, 
}
