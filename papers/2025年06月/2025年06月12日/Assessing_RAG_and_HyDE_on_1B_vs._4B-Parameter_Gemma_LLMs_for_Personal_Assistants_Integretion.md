# 评测 RAG 与 HyDE 在 10B vs. 40B 参数 Gemma LLM 中的应用效果，应用于个人助理集成

发布时间：2025年06月12日

`LLM应用` `知识图谱`

> Assessing RAG and HyDE on 1B vs. 4B-Parameter Gemma LLMs for Personal Assistants Integretion

# 摘要

> <翻译失败>

> Resource efficiency is a critical barrier to deploying large language models (LLMs) in edge and privacy-sensitive applications. This study evaluates the efficacy of two augmentation strategies--Retrieval-Augmented Generation (RAG) and Hypothetical Document Embeddings (HyDE)--on compact Gemma LLMs of 1 billion and 4 billion parameters, within the context of a privacy-first personal assistant. We implement short-term memory via MongoDB and long-term semantic storage via Qdrant, orchestrated through FastAPI and LangChain, and expose the system through a React.js frontend. Across both model scales, RAG consistently reduces latency by up to 17\% and eliminates factual hallucinations when responding to user-specific and domain-specific queries. HyDE, by contrast, enhances semantic relevance--particularly for complex physics prompts--but incurs a 25--40\% increase in response time and a non-negligible hallucination rate in personal-data retrieval. Comparing 1 B to 4 B models, we observe that scaling yields marginal throughput gains for baseline and RAG pipelines, but magnifies HyDE's computational overhead and variability. Our findings position RAG as the pragmatic choice for on-device personal assistants powered by small-scale LLMs.

[Arxiv](https://arxiv.org/abs/2506.21568)