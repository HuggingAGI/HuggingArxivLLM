# 超越虚假信号：基于反事实推理与自适应专家路由的多模态大型语言模型去偏

发布时间：2025年09月18日

`LLM应用` `媒体与娱乐`

> Beyond Spurious Signals: Debiasing Multimodal Large Language Models via Counterfactual Inference and Adaptive Expert Routing

# 摘要

> 多模态大型语言模型（MLLMs）虽在整合视觉与文本信息方面展现出强大能力，却常依赖虚假相关性，这削弱了它们在复杂多模态推理任务中的鲁棒性与泛化性。本文提出一种新颖的基于因果中介的去偏框架，旨在攻克MLLMs中的表层相关偏差这一核心难题。具体而言，我们借助反事实例子剥离核心语义与虚假文本、视觉上下文的干扰，以激活训练阶段的去偏机制；同时采用带动态路由的混合专家（MoE）架构，实现对特定模态去偏专家的精准调用。在多模态讽刺检测与情感分析任务上的实证结果显示，该框架性能远超单模态去偏策略及现有最先进模型。

> Multimodal Large Language Models (MLLMs) have shown substantial capabilities in integrating visual and textual information, yet frequently rely on spurious correlations, undermining their robustness and generalization in complex multimodal reasoning tasks. This paper addresses the critical challenge of superficial correlation bias in MLLMs through a novel causal mediation-based debiasing framework. Specially, we distinguishing core semantics from spurious textual and visual contexts via counterfactual examples to activate training-stage debiasing and employ a Mixture-of-Experts (MoE) architecture with dynamic routing to selectively engages modality-specific debiasing experts. Empirical evaluation on multimodal sarcasm detection and sentiment analysis tasks demonstrates that our framework significantly surpasses unimodal debiasing strategies and existing state-of-the-art models.

[Arxiv](https://arxiv.org/abs/2509.15361)