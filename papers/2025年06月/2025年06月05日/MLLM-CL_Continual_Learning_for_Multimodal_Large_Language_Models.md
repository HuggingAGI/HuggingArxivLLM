# MLLM-CL：持续学习在多模态大型语言模型中的应用

发布时间：2025年06月05日

`LLM应用` `多模态模型` `持续学习`

> MLLM-CL: Continual Learning for Multimodal Large Language Models

# 摘要

> 近期，多模态大型语言模型（MLLMs）在视觉语言理解领域表现优异，但在动态现实场景中持续整合新知识与技能方面仍面临挑战。尽管持续学习（CL）提供了解决思路，但现有方法和基准却存在明显局限。本文提出MLLM-CL，一个涵盖领域和能力的持续学习新型基准。其中，领域学习专注于在主流领域中进行独立且相同分布（IID）评估，能力学习则针对非IID场景，关注模型新兴能力。方法上，我们通过参数隔离防止灾难性干扰，并引入基于MLLM的路由机制。实验结果表明，该方法能以最小遗忘整合知识与能力，显著超越现有方案。

> Recent Multimodal Large Language Models (MLLMs) excel in vision-language understanding but face challenges in adapting to dynamic real-world scenarios that require continuous integration of new knowledge and skills. While continual learning (CL) offers a potential solution, existing benchmarks and methods suffer from critical limitations. In this paper, we introduce MLLM-CL, a novel benchmark encompassing domain and ability continual learning, where the former focuses on independently and identically distributed (IID) evaluation across evolving mainstream domains, whereas the latter evaluates on non-IID scenarios with emerging model ability. Methodologically, we propose preventing catastrophic interference through parameter isolation, along with an MLLM-based routing mechanism. Extensive experiments demonstrate that our approach can integrate domain-specific knowledge and functional abilities with minimal forgetting, significantly outperforming existing methods.

[Arxiv](https://arxiv.org/abs/2506.05453)