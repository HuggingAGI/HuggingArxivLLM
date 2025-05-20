# # EpiLLM：解锁大型语言模型在疫情预测中的潜力

发布时间：2025年05月19日

`LLM应用` `公共卫生` `流行病学`

> EpiLLM: Unlocking the Potential of Large Language Models in Epidemic Forecasting

# 摘要

> 精准的流行病预测对公共卫生安全具有战略意义。尽管大型语言模型（LLMs）在特定领域任务中表现出色，但其在流行病预测中的潜力尚未充分挖掘。本文提出了一种专为时空流行病预测设计的全新框架——EpiLLM。考虑到真实世界中流行病传播的关键因素：感染病例数和人类移动性，我们设计了一种双分支架构，实现复杂流行病模式与语言令牌的细粒度对齐。为释放LLM在多步预测和泛化方面的潜力，我们提出了一种自回归建模范式，将流行病预测转化为下一步令牌预测任务。此外，我们引入了时空提示学习技术，从数据驱动的角度增强LLM的预测能力。实验结果表明，EpiLLM在真实COVID-19数据集上显著超越现有方法，并展现出典型的LLM扩展特性。

> Advanced epidemic forecasting is critical for enabling precision containment strategies, highlighting its strategic importance for public health security. While recent advances in Large Language Models (LLMs) have demonstrated effectiveness as foundation models for domain-specific tasks, their potential for epidemic forecasting remains largely unexplored. In this paper, we introduce EpiLLM, a novel LLM-based framework tailored for spatio-temporal epidemic forecasting. Considering the key factors in real-world epidemic transmission: infection cases and human mobility, we introduce a dual-branch architecture to achieve fine-grained token-level alignment between such complex epidemic patterns and language tokens for LLM adaptation. To unleash the multi-step forecasting and generalization potential of LLM architectures, we propose an autoregressive modeling paradigm that reformulates the epidemic forecasting task into next-token prediction. To further enhance LLM perception of epidemics, we introduce spatio-temporal prompt learning techniques, which strengthen forecasting capabilities from a data-driven perspective. Extensive experiments show that EpiLLM significantly outperforms existing baselines on real-world COVID-19 datasets and exhibits scaling behavior characteristic of LLMs.

[Arxiv](https://arxiv.org/abs/2505.12738)