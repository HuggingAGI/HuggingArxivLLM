# <翻译失败>

发布时间：2025年08月30日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `（由于论文摘要翻译失败` `无法获取内容信息` `故无法确定行业标签）`

> ERank: Fusing Supervised Fine-Tuning and Reinforcement Learning for Effective and Efficient Text Reranking

# 摘要

> <翻译失败>

> Text reranking models are a crucial component in modern systems like Retrieval-Augmented Generation, tasked with selecting the most relevant documents prior to generation. However, current Large Language Models (LLMs) powered rerankers often face a fundamental trade-off. On one hand, Supervised Fine-Tuning based pointwise methods that frame relevance as a binary classification task lack the necessary scoring discrimination, particularly for those built on reasoning LLMs. On the other hand, approaches designed for complex reasoning often employ powerful yet inefficient listwise formulations, rendering them impractical for low latency applications. To resolve this dilemma, we introduce ERank, a highly effective and efficient pointwise reranker built from a reasoning LLM that excels across diverse relevance scenarios. We propose a novel two-stage training pipeline that begins with Supervised Fine-Tuning (SFT). In this stage, we move beyond binary labels and train the model generatively to output fine grained integer scores, which significantly enhances relevance discrimination. The model is then further refined using Reinforcement Learning (RL) with a novel, listwise derived reward. This technique instills global ranking awareness into the efficient pointwise architecture. We evaluate the ERank reranker on the BRIGHT, FollowIR, TREC DL, and BEIR benchmarks, demonstrating superior effectiveness and robustness compared to existing approaches. On the reasoning-intensive BRIGHT benchmark, our ERank-4B achieves an nDCG@10 of 38.7, while a larger 32B variant reaches a state of the art nDCG@10 of 40.2.

[Arxiv](https://arxiv.org/abs/2509.00520)