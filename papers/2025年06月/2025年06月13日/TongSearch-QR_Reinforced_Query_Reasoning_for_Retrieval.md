# # TongSearch-QR：强化查询推理，助力检索优化

发布时间：2025年06月13日

`LLM应用` `信息检索`

> TongSearch-QR: Reinforced Query Reasoning for Retrieval

# 摘要

> 传统信息检索方法在文本和语义匹配上表现出色，但在需要多跳推理或多复杂语义理解的推理密集型检索任务中表现欠佳。为解决这一问题，我们提出了一种基于大型语言模型（LLMs）显式重写或增强查询的方法，在检索前提取与推理相关的内容。然而，由于GPT-4或LLaMA3-70B等大规模语言模型的高推理成本及其在实际系统中有限的部署能力，它们的大规模应用仍不切实际。为应对这一挑战，我们引入了TongSearch QR（曾称为“TongSearch Reasoner”），这是一个专注于推理密集型检索中查询推理和重写的轻量级语言模型系列。通过一种新颖的半规则奖励函数，我们采用强化学习方法，使较小规模的语言模型（如Qwen2.5-7B-Instruct和Qwen2.5-1.5B-Instruct）能够达到与大规模语言模型相当的查询推理性能，而无需承担其高昂的推理成本。实验结果表明，在BRIGHT基准测试中，以BM25作为检索器，TongSearch QR-7B和TongSearch QR-1.5B模型均显著超越现有基线，包括基于提示的查询推理器和一些专为推理密集型检索任务训练的最新密集检索器，展现出卓越的现实部署适应性。

> Traditional information retrieval (IR) methods excel at textual and semantic matching but struggle in reasoning-intensive retrieval tasks that require multi-hop inference or complex semantic understanding between queries and documents. One promising solution is to explicitly rewrite or augment queries using large language models (LLMs) to elicit reasoning-relevant content prior to retrieval. However, the widespread use of large-scale language models like GPT-4 or LLaMA3-70B remains impractical due to their high inference cost and limited deployability in real-world systems. In this work, we introduce TongSearch QR (Previously Known as "TongSearch Reasoner"), a family of small-scale language models for query reasoning and rewriting in reasoning-intensive retrieval. With a novel semi-rule-based reward function, we employ reinforcement learning approaches enabling smaller language models, e,g, Qwen2.5-7B-Instruct and Qwen2.5-1.5B-Instruct, to achieve query reasoning performance rivaling large-scale language models without their prohibitive inference costs. Experiment results on BRIGHT benchmark show that with BM25 as retrievers, both TongSearch QR-7B and TongSearch QR-1.5B models significantly outperform existing baselines, including prompt-based query reasoners and some latest dense retrievers trained for reasoning-intensive retrieval tasks, offering superior adaptability for real-world deployment.

[Arxiv](https://arxiv.org/abs/2506.11603)