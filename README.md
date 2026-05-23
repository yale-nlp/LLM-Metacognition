<h1 align="center"> 🔎 Metacognition in LLMs: <br>Foundations, Progress, and Opportunities </h1>

<div align="center">

[![PDF](https://img.shields.io/badge/PDF-Download-red?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](https://github.com/yale-nlp/LLM-Metacognition/paper.pdf) [![arXiv](https://img.shields.io/badge/arXiv-XXXX-b31b1b?style=for-the-badge)](https://arxiv.org/abs/xxxx) 

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/yale-nlp/LLM-Metacognition?style=social)](https://github.com/yale-nlp/LLM-Metacognition/stargazers)

</div>

<!-- This repository contains an organized collection of papers related to metacognition in large language xmodels (LLMs). These papers are organized according to our paper [Metacognition in LLMs: Foundations, Progress, and Opportunities](link). -->

<!-- **Metacognition** is a foundational component of intelligence that has become increasingly recognized as a cornerstone of capable, transparent AI systems in recent years. It is critical to effective learning, problem solving, decision-making, communication, and more. Yet while LLMs have made significant progress across diverse real-world tasks, it remains unclear when, how, and to what extent they can exhibit or be endowed with effective metacognitive abilities—and how such abilities can be adapted to advance the fundamental capabilities, reliability, and intelligence of AI systems.  -->

This repository provides an organized collection of papers related to metacognition in LLMs, reviewed in our survey [Metacognition in LLMs: Foundations, Progress, and Opportunities](). We comprehensively and systematically taxonomize the landscape of this emerging field, summarizing existing methods and benchmarks to measure and elicit LLMs' metacognitive abilities, techniques to develop, improve, and apply models' metacognitive skills, and findings and implications of ongoing research. We also discuss applications, open challenges, and promising directions for future work. We hope this can serve as a detailed, up-to-date reference and stimulate meaningful research and discussion.

## 🌟 Citation

If you find this survey or repository useful for your research, please cite:

```bibtex
Coming soon!
```

## 📧 Contact
Feel free to open an issue or contact us if you have any feedback or want to include your work in this list!

Corresponding Author: Kaili Liu (kaili.liu@yale.edu)


## 📖 Table of Contents
<!-- - [🚀 Overview](#-overview) -->
<!-- - [📄 Paper List](#-paper-list) -->
- [0. Metacognition Background](#0-metacognition-background)
- [1. Measuring Metacognition in LLMs](#1-measuring-metacognition-in-llms)
    - [Psychologically-Grounded Methods](#psychologically-grounded-methods)
    - [Neurofeedback-Based Methods](#neurofeedback-based-methods)
    - [Confidence-Based Methods](#confidence-based-methods)
    - [Interpretability-Based Methods](#interpretability-based-methods)
    - [Task-Specific Methods](#task-specific-methods)
    - [Benchmarks](#benchmarks)
- [2. Current Findings on Metacognition in LLMs](#2-current-findings-on-metacognition-in-llms)
- [3. Implementing Metacognition in LLMs](#3-implementing-metacognition-in-llms)
    - [Metacognition for LLMs](#metacognition-for-llms)
    - [Metacognition for Reasoning Models](#metacognition-for-reasoning-models)
    - [Metacognition for LLM Agents](#metacognition-for-llm-agents)
- [4. Metacognitive Methods to Improve Capabilities of LLMs](#4-metacognitive-methods-to-improve-capabilities-of-llms)
    - [General Capabilities](#general-capabilities)
    - [Confidence Calibration](#confidence-calibration)
    - [Hallucination Detection](#hallucination-reduction)
    - [Knowledge Boundary Detection](#knowledge-boundary-detection)
    - [Resistance to Persuasion](#resistance-to-persuasion)
    - [Interpretability](#interpretability)
    - [Reasoning for Non-Reasoning Models](#reasoning-for-non-reasoning-models)
    - [Retrieval](#retrieval)
    - [Self-Improvement](#self-improvement)
    - [Other Abilities](#other-abilities)
- [5. Applications of LLM Metacognition](#5-applications-of-llm-metacognition)
    - [Human-AI Decision-Making](#human-ai-decision-making)
    - [User Simulation](#user-simulation)
    - [Pedagogy](#pedagogy)
- [6. Broader Directions](#6-broader-directions)
- [7. Other Resources](#7-other-resources)
<!-- - [Contact](#-contact) -->


## 📄 Paper List

### 0. Metacognition Background

> **Metacognition** is a foundational component of intelligence that is critical to effective learning, problem solving, decision-making, communication, and more. In recent years, it has become increasingly recognized as a cornerstone of capable, transparent AI systems.

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]


### 1. Measuring Metacognition in LLMs

<!-- while LLMs have made significant progress across diverse real-world tasks, it remains unclear when, how, and to what extent they can exhibit or be endowed with effective metacognitive abilities—and how such abilities can be adapted to advance the fundamental capabilities, reliability, and intelligence of AI systems.  -->

#### _Psychologically-Grounded Methods_
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
100. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### _Neurofeedback-Based Methods_
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### _Confidence-Based Methods_
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### _Interpretability-Based Methods_
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### _Task-Specific Methods_
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### _Benchmarks_
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

### 2. Current Findings on Metacognition in LLMs
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

### 3. Implementing Metacognition in LLMs

#### _Metacognition for LLMs_

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]


#### _Metacognition for Reasoning Models_

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]


#### _Metacognition for LLM Agents_

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

<!-- ### 4. Applying Metacognition to Improve Capabilities of LLMs -->
### 4. Metacognitive Methods to Improve Capabilities of LLMs

#### General Capabilities

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### Confidence Calibration

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### Hallucination Reduction

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### Knowledge Boundary Detection

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### Resistance to Persuasion

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### Interpretability

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### Reasoning for Non-Reasoning Models

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### Retrieval

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]


#### Self-Improvement

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### Other Abilities

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

### 5. Applications of LLM Metacognition

#### Human-AI Decision-Making

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### User Simulation

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

#### Pedagogy

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

### 6. Broader Directions

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]

### 7. Other Resources

1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]
1. **Query2doc: Query Expansion with Large Language Models**, _Wang et al._, EMNLP 2023. \[[Paper](https://aclanthology.org/2023.emnlp-main.585.pdf)\]


<!-- ## 🚀 Update Log
- Version 4 \[2025-09-17\]
  - Search Agent: We reformulate the search agent section.
  - Reranker: We add several listwise rerankers and Section 'Reasoning-intensive Rerankers'.
- Version 3 \[2024-09-03\]
  - We refine the background to pay more attention to IR.
  - Rewriter: We add a new section "Formats of Rewritten Queries" to provide a more clear classfication and incorporated up-to-date methods.
  - Retriever: We incorporated up-to-date methods that utilize LLM to enlarge the dataset used for training retrievers or to improve the overall structure and design of retriever systems.
  - Reranker: We have added some unsupervised rerankers, several studies focusing on training data augmentation, and discussions on the limitations of LLM rerankers.
  - Reader: We added the latest studies on readers, particularly enriching the works in the active reader section.
  - Search Agent: We added the latest studies on static and dynamic search agents, particularly enriching the works in benchmarking and self-planning.

- Version 2 \[2024-01-19\]
  - We added a new section to introduce search agents, which represent an innovative approach to integrating LLMs with IR systems.
  - Rewriter:  We added recent works on LLM-based query rewriting, most of which focus on conversational search.
  - Retriever: We added the latest techniques that leverage LLMs to expand the training corpus for retrievers or to enhance retrievers' architectures.
  - Reranker: We added recent LLM-based ranking works to each of the three part: Utilizing LLMs as Supervised Rerankers, Utilizing LLMs as Unsupervised Rerankers, and Utilizing LLMs for Training Data Augmentation.
  - Reader: We added the latest studies in LLM-enhanced reader area, including a section introducing the reference compression technique, a section discussing the applications of LLM-enhanced readers, and a section analyzing the characteristics of LLM-enhanced readers.
  - Future Direction: We added a section about search agents and a section discussing the bias caused by leveraging LLMs into IR systems. -->


<!-- - [Overview](#-overview) -->
<!-- - [Latest News](#-latest-news) -->
<!-- - [Taxonomy & Legends](#-taxonomy--legends) -->

<!-- ## 📋 Table of Content
- [Query Rewriter](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#query-rewriter)
  - [Prompting Methods](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#prompting-methods)
  - [Fine-tuning Methods](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#fine-tuning-methods)
  - [Knowledge Distillation Methods](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#knowledge-distillation-methods)
- [Retriever](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#retriever)
  - [Leveraging LLMs to Generate Search Data](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#leveraging-llms-to-generate-search-data)
  - [Employing LLMs to Enhance Model Architecture](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#employing-llms-to-enhance-model-architecture)
- [Re-ranker](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#re-ranker)
  - [Utilizing LLMs as Supervised Rerankers](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#utilizing-llms-as-supervised-rerankers)
  - [Utilizing LLMs as Unsupervised Rerankers](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#utilizing-llms-as-unsupervised-rerankers)
  - [Utilizing LLMs for Training Data Augmentation](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#utilizing-llms-for-training-data-augmentation)
  - [Reasoning-intensive Rerankers](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#reasoning-intensive-rerankers)
- [Reader](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#reader)
  - [Passive Reader](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#passive-reader)
  - [Active Reader](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#active-reader)
  - [Compressor](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#compressor)
  - [Analysis](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#analysis)
  - [Applications](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#applications)
- [Search Agent](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#search-agent)
  - [Information Seeking Module](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#information-seeking-module)
- [Other Resources](https://github.com/RUC-NLPIR/LLM4IR-Survey/tree/main#other-resources) -->

<!-- ## 🔥 Latest News -->
<!-- - **[2026-XX-XX]** Our paper is available on arXiv! Check it out [here](https://arxiv.org/abs/2601.14004). -->
<!-- - **[2026-06-01]** This repository is created to track the latest progress on metacognition in LLMs. -->