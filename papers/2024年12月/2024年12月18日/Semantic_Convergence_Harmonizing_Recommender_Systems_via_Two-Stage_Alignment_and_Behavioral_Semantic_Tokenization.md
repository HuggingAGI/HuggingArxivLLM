# 语义收敛：借助两阶段对齐与行为语义标记化来协调推荐系统

发布时间：2024年12月18日

`LLM应用` `推荐系统`

> Semantic Convergence: Harmonizing Recommender Systems via Two-Stage Alignment and Behavioral Semantic Tokenization

# 摘要

> 大型语言模型（LLMs）具备卓越的推理能力，能够从用户的历史行为中敏锐地捕捉到深层兴趣，为推荐系统的进步开辟了光明前景。然而，推荐系统常见的稀疏协作语义与LLMs里的密集令牌表征存在明显差异。在本研究中，我们提出了一个创新框架，将传统推荐模型与LLMs的强大功能完美融合。我们借助所提出的对齐标记化模块，把ItemIDs转化为与LLMs空间语义相符的序列，以此开启融合进程。另外，我们还设计了一系列专门的监督学习任务，旨在让协作信号与自然语言语义的细微之处相契合。为保证实际应用效果，我们通过为每位用户预缓存前K个结果来优化在线推理，降低延迟，提升效率。大量实验表明，我们的模型显著提升了召回指标，展现出推荐系统出色的可扩展性。

> Large language models (LLMs), endowed with exceptional reasoning capabilities, are adept at discerning profound user interests from historical behaviors, thereby presenting a promising avenue for the advancement of recommendation systems. However, a notable discrepancy persists between the sparse collaborative semantics typically found in recommendation systems and the dense token representations within LLMs. In our study, we propose a novel framework that harmoniously merges traditional recommendation models with the prowess of LLMs. We initiate this integration by transforming ItemIDs into sequences that align semantically with the LLMs space, through the proposed Alignment Tokenization module. Additionally, we design a series of specialized supervised learning tasks aimed at aligning collaborative signals with the subtleties of natural language semantics. To ensure practical applicability, we optimize online inference by pre-caching the top-K results for each user, reducing latency and improving effciency. Extensive experimental evidence indicates that our model markedly improves recall metrics and displays remarkable scalability of recommendation systems.

[Arxiv](https://arxiv.org/abs/2412.13771)