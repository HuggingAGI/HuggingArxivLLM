# 按需辩论：自适应多智能体协作助力高效LLM推理

发布时间：2025年04月07日

`LLM应用` `人工智能`

> Debate Only When Necessary: Adaptive Multiagent Collaboration for Efficient LLM Reasoning

# 摘要

> 多智能体协作在提升大型语言模型（LLMs）推理能力方面展现出巨大潜力，但其迭代交互过程导致了较高的计算开销。此外，对无需协作的查询开展辩论反而可能增加错误风险。为解决这些问题，我们提出了“仅在必要时辩论”（DOWN）框架。该框架基于智能体初始响应的信心分数，选择性地激活辩论过程。对于触发辩论的查询，智能体利用参与者的响应及其信心分数优化输出。实验结果表明，DOWN在保持甚至超越现有协作系统性能的同时，显著提升了效率。研究还发现，基于信心的辩论机制能有效抑制错误传播，促进可靠响应的整合。这些成果确立了DOWN作为高效多智能体推理优化策略的地位，为LLM协作的实际应用提供了有力支持。

> Multiagent collaboration has emerged as a promising framework for enhancing the reasoning capabilities of large language models (LLMs). While this approach improves reasoning capability, it incurs substantial computational overhead due to iterative agent interactions. Furthermore, engaging in debates for queries that do not necessitate collaboration amplifies the risk of error generation. To address these challenges, we propose Debate Only When Necessary (DOWN), an adaptive multiagent debate framework that selectively activates the debate process based on the confidence score of the agent's initial response. For queries where debate is triggered, agents refine their outputs using responses from participating agents and their confidence scores. Experimental results demonstrate that this mechanism significantly improves efficiency while maintaining or even surpassing the performance of existing multiagent debate systems. We also find that confidence-guided debate mitigates error propagation and enhances the selective incorporation of reliable responses. These results establish DOWN as an optimization strategy for efficient and effective multiagent reasoning, facilitating the practical deployment of LLM-based collaboration.

[Arxiv](https://arxiv.org/abs/2504.05047)