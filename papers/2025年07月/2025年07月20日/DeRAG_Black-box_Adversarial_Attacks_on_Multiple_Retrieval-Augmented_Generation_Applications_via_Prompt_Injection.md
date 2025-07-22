# DeRAG：通过提示注入对多个检索增强生成应用实施黑盒对抗攻击。

发布时间：2025年07月20日

`RAG` `问答系统` `对抗性攻击`

> DeRAG: Black-box Adversarial Attacks on Multiple Retrieval-Augmented Generation Applications via Prompt Injection

# 摘要

> 对抗性提示攻击能通过重新排序检索增强生成（RAG）系统，使其输出错误结果，从而显著影响其可靠性。本文提出了一种创新方法，将差分进化（DE）应用于优化基于RAG问答系统的对抗性提示后缀。这种方法无需梯度信息，将RAG管道视为黑箱，通过进化候选后缀种群，使目标错误文档的检索排名更贴近真实场景。我们在BEIR问答数据集上进行了实验，评估了在多个检索应用下，攻击在特定检索排名阈值下的成功率。实验结果表明，与针对密集检索器的GGPP和针对稀疏检索器的PRADA相比，DE基的提示优化在某些情况下达到了更具竞争力（甚至更高的）成功率，同时仅使用了少量的对抗性后缀令牌（<=5个）。此外，我们引入了一种可读性感知的后缀构造策略，并通过Welch's t-test验证了该策略显著降低了MLM的负对数似然。通过BERT基的对抗性后缀检测器评估，我们发现DE生成的后缀能够规避检测，检测准确率接近随机水平。

> Adversarial prompt attacks can significantly alter the reliability of Retrieval-Augmented Generation (RAG) systems by re-ranking them to produce incorrect outputs. In this paper, we present a novel method that applies Differential Evolution (DE) to optimize adversarial prompt suffixes for RAG-based question answering. Our approach is gradient-free, treating the RAG pipeline as a black box and evolving a population of candidate suffixes to maximize the retrieval rank of a targeted incorrect document to be closer to real world scenarios. We conducted experiments on the BEIR QA datasets to evaluate attack success at certain retrieval rank thresholds under multiple retrieving applications. Our results demonstrate that DE-based prompt optimization attains competitive (and in some cases higher) success rates compared to GGPP to dense retrievers and PRADA to sparse retrievers, while using only a small number of tokens (<=5 tokens) in the adversarial suffix. Furthermore, we introduce a readability-aware suffix construction strategy, validated by a statistically significant reduction in MLM negative log-likelihood with Welch's t-test. Through evaluations with a BERT-based adversarial suffix detector, we show that DE-generated suffixes evade detection, yielding near-chance detection accuracy.

[Arxiv](https://arxiv.org/abs/2507.15042)