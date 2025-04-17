# d1: 通过强化学习扩展扩散大型语言模型的推理能力

发布时间：2025年04月16日

`LLM理论` `人工智能`

> d1: Scaling Reasoning in Diffusion Large Language Models via Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）近期展现出强大的推理能力，这些能力得益于在线强化学习（RL）。这些能力主要在左到右的自回归（AR）生成范式中得到体现。相比之下，基于扩散的非自回归范式采用粗到细的文本生成方式。尽管最近的基于扩散的大型语言模型（dLLMs）在语言建模性能上与自回归模型相当，但它们是否能利用大型语言模型推理的最新进展仍不明朗。为此，我们提出了d1框架，通过结合监督微调（SFT）和强化学习（RL），将预训练的掩蔽dLLMs适配为推理模型。具体而言，我们开发并扩展了提升预训练dLLMs推理能力的技术：(a) 引入一种掩蔽的SFT技术，直接从现有数据集中提炼知识并灌输自我改进行为；(b) 提出了一种新颖的无批评、基于策略梯度的RL算法——diffu-GRPO。通过实证研究，我们评估了不同后训练方案在多个数学和逻辑推理基准上的表现。结果表明，d1不仅提供了最佳性能，还显著提升了最先进的dLLM的推理能力。

> Recent large language models (LLMs) have demonstrated strong reasoning capabilities that benefits from online reinforcement learning (RL). These capabilities have primarily been demonstrated within the left-to-right autoregressive (AR) generation paradigm. In contrast, non-autoregressive paradigms based on diffusion generate text in a coarse-to-fine manner. Although recent diffusion-based large language models (dLLMs) have achieved competitive language modeling performance compared to their AR counterparts, it remains unclear if dLLMs can also leverage recent advances in LLM reasoning. To this end, we propose d1, a framework to adapt pre-trained masked dLLMs into reasoning models via a combination of supervised finetuning (SFT) and RL. Specifically, we develop and extend techniques to improve reasoning in pretrained dLLMs: (a) we utilize a masked SFT technique to distill knowledge and instill self-improvement behavior directly from existing datasets, and (b) we introduce a novel critic-free, policy-gradient based RL algorithm called diffu-GRPO. Through empirical studies, we investigate the performance of different post-training recipes on multiple mathematical and logical reasoning benchmarks. We find that d1 yields the best performance and significantly improves performance of a state-of-the-art dLLM.

[Arxiv](https://arxiv.org/abs/2504.12216)