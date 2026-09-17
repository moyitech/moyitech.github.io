---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

**Zeyu Wang** · MPhil student at The Hong Kong University of Science and Technology (Guangzhou)<br>
[Email](mailto:admin@9998k.cn) · [GitHub](https://github.com/moyitech) · [Google Scholar](https://scholar.google.com/citations?user=fC9fhY8AAAAJ) · [Blog](https://www.9998k.cn/)

## Education

### The Hong Kong University of Science and Technology (Guangzhou)

Research Master's in Artificial Intelligence<br>
September 2026–June 2028 (expected)

### Taiyuan University of Technology

Bachelor's in Computer Science and Technology · **Comprehensive Assessment Rank: 2/149**<br>
September 2022–June 2026

## Research Interests & Skills

- **Research interests:** LLM post-training, reinforcement learning, controllable generation, RAG, and AI agents.
- **Language models:** SFT, PPO, GRPO, multi-GPU training, local deployment with vLLM and llama.cpp, and domain-specific agent development.
- **Deep learning:** PyTorch, neural network implementation, and model training.
- **Engineering:** Python, Linux, Docker, Milvus, and research compute server administration.

## Research Experience

### IDEA — Controllable Creative Writing

International Digital Economy Academy (IDEA)<br>
July 2025–April 2026

- Optimized short-form video script generation, migrating from a hosted R1 API to a local Qwen2.5-7B model.
- Used expert-guided cold-start examples, distillation, and data filtering to improve the training data.
- Applied GRPO with natural-language critiques as a non-rule-based reward, improving evaluation dimensions including informativeness and rhetorical quality.
- Related paper: *From Homogeneity to Diversity: Self-Refined GRPO for Controllable Creative Writing*, accepted to **Findings of EMNLP 2026**; full author list below.

### MIHRI Lab, Taiyuan University of Technology — Audio-Visual Speaker Tracking

May 2024–December 2024

- Contributed to *Multi-Stage Multimodal Distillation for Audio-Visual Speaker Tracking*, published at ICASSP 2025, as the third author.
- Used SiamFC and stGCF in an audio-visual network with three-stage distillation from two unimodal teachers and symmetric cross-attention for student modality fusion.
- Evaluated on AV16.3, training on sequences 1, 2, and 3 and testing on sequences 8, 11, and 12; achieved a mean absolute error of **3.02 pixels**.

## Papers

- **From Homogeneity to Diversity: Self-Refined GRPO for Controllable Creative Writing**<br>
  Minna Peng, Wei Tan, **Zeyu Wang**, Yongquan Hu, Ruizhi Huang, Yang Jie.<br>
  *Accepted to Findings of EMNLP 2026.*
- **Multi-Stage Multimodal Distillation for Audio-Visual Speaker Tracking**<br>
  Yidi Li, Wenkai Zhao, **Zeyu Wang**, Zhenhuan Xu, Bin Ren, Nicu Sebe.<br>
  *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2025.*<br>
  DOI: [10.1109/ICASSP49660.2025.10888838](https://doi.org/10.1109/ICASSP49660.2025.10888838)

## Internships

### Baidu — NLP Algorithm Intern

May 2025–July 2025

- Improved e-commerce search term extraction from user queries, increasing **micro-F1 from 83.2% to 87.3%**.
- Applied Search-R1-inspired methods so the model could decide when to retrieve external information and generate search terms.
- Used GPT-4o to assist annotation of **10,000 examples**, including **3,000 cold-start examples**.
- Trained Qwen2.5-7B with GRPO and rule-based rewards.

### SentimenTrader — AI Agent Algorithm Intern

October 2024–April 2025

- Developed an AutoAgent for paid users, combining financial articles, YouTube content, and stock backtesting tools for decision support.
- Analyzed user intent and information completeness, then used retrieved context to guide iterative web operations for backtesting.
- Used multiple function calls to extract semantic queries and keywords for parallel retrieval with bge-large and BM25, alongside time-range and fuzzy-match filters.
- Reranked results with bge-rerank and used GPT-4o-mini for query-conditioned processing of retrieved content.

### Strikingly — RAG Development Intern

December 2023–June 2024

- Developed two GPT-4-based RAG applications for an international customer-service team, improving efficiency by **60%+**.
- Built domain-aware translation with Milvus and a terminology knowledge base, returning structured JSON lists for conversations with complex context.
- Built support QA with document chunking and Agentic RAG, returning answers with source links; achieved **92% recall** and **0.78 MRR**.

## Open Source

### [self-llm](https://github.com/datawhalechina/self-llm)

Core contributor · August 2024–October 2025

- Contributed Qwen3 architecture analysis and explanations of the Kimi-VL-A3B technical report.
- Contributed OpenELM LoRA fine-tuning and deployment materials covering WebDemo, vLLM, and FastAPI.
- The project was selected as an outstanding open-source algorithm project case at the 2024 Google Developer Conference.

### [Mutual-AI](https://github.com/YinHan-Zhang/Mutual-AI)

Core contributor — algorithms and infrastructure · April 2023–August 2023

- Built introductory CV and NLP demos for interactive learning as part of TYUT's Yunding Academy AI learning activities.
- Trained a CNN for handwritten digit recognition and fine-tuned BERT on Weibo comments for binary sentiment classification.
- Integrated models with FastAPI and managed distributed deployment across five servers.

## Projects

### TYUT AI Counselor

Initiator and lead developer · February 2025–March 2025<br>
[Project introduction](https://mp.weixin.qq.com/s/It5YYVXDfUXFA7APnv7kkg)

- Built a campus information assistant used **100,000+ times** across the university. The project received **RMB 30,000 in project payments** and was featured in *Shanxi Daily*.
- Collected university notices using crawlers and supported PDF and CSV knowledge-base management with MySQL and Milvus.
- Exposed BM25 and embedding retrieval as tools, used Doubao-1.5-lite to extract queries and call the tools, and generated responses with DeepSeek-v3.
- Screened inputs alongside retrieval to distinguish campus questions, prompt injections, and unrelated content; interrupted inappropriate requests with predefined responses.

### Home Agent

Team leader and lead developer · December 2025

- Extended Blockly to integrate Xiaomi smart-home APIs.
- Fine-tuned Qwen3 with LoRA to convert natural-language requests into JSON representations of blocks, using few-shot examples generated by GPT-4o.
- Won the **Hardcore Technology Award (1/98)** at the Qwen On-Device AI Innovation Challenge, with **RMB 50,000 in prize money**.

### AI Interviewer

Team leader and lead developer · December 2023

- Built a multi-agent workflow covering resume assessment, RAG-based interview question retrieval, answer evaluation, and final scoring.
- Combined crawled AI interview questions with GPT-generated questions and built a retrieval tool with FAISS.
- Received a technology award in the Alibaba Cloud Tianchi AgentBuilder Challenge, with **RMB 10,000 in prize money**.

## Awards

- **April 2026 — National Second Prize & First Place in Shanxi Province**, National College Student Career Planning Competition.
- **December 2025 — Hardcore Technology Award (1/98)**, Qwen On-Device AI Innovation Challenge; team leader.
- **September 2025 — AMD Hardware Optimization Award (2/50)**, Alibaba ModelScope MCP & Agent Challenge; team leader.
- **May 2025 — Shanxi Provincial Special Prize**, Challenge Cup; team leader.
- **November 2024 — National Second Prize**, Global Campus Artificial Intelligence Algorithm Elite Competition; team leader.
- **November 2024 — International First Prize**, International Youth Artificial Intelligence Competition; team leader.
- **September 2024 — National Special Prize (1/380)**, China University Students' Intelligent Lighting and Intelligent Wearable Innovation and Entrepreneurship Competition; team leader.
- **December 2023 — NVIDIA Technology Award (4/650)**, Alibaba Cloud Tianchi AgentBuilder Challenge; team leader.
- **November 2023 — National Third Prize (7/2221)**, China Mobile Wutong Cup Big Data Competition.
- **September 2023 — National Second Prize**, China Undergraduate Mathematical Contest in Modeling.
