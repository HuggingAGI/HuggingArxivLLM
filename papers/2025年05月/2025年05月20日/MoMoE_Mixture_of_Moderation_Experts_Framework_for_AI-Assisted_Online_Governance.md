# MoMoE: 一种用于人工智能辅助在线治理的中立专家混合框架

发布时间：2025年05月20日

`LLM应用` `内容审核` `社区管理`

> MoMoE: Mixture of Moderation Experts Framework for AI-Assisted Online Governance

# 摘要

> 大型语言模型（LLMs）在识别在线社区中的有害内容方面展现出了巨大潜力。然而，现有的内容审核方法需要为每个社区单独训练模型，并且其决策过程不透明，这限制了其在实际中的应用。我们提出了内容审核专家混合模型（MoMoE），这是一个模块化、跨社区的框架，能够在可扩展的内容审核中添加事后解释。MoMoE协调四个操作——分配、预测、聚合、解释，并具体实现为七种社区专用专家（MoMoE-Community）和五种违规行为专家（MoMoE-NormVio）。在30个未见过的subreddits上，最佳变体分别获得了0.72和0.67的微F1分数，与强大的微调基线相当或更优，同时始终生成简洁可靠的解释。尽管社区专用专家提供了最高的峰值准确率，违规行为专家在跨领域中提供了更稳定的表现。这些发现表明，MoMoE可以在无需针对每个社区进行微调的情况下实现可扩展且透明的内容审核。更广泛地说，它们表明轻量级、可解释的专家集合可以指导未来关于可信人机协作治理的研究。

> Large language models (LLMs) have shown great potential in flagging harmful content in online communities. Yet, existing approaches for moderation require a separate model for every community and are opaque in their decision-making, limiting real-world adoption. We introduce Mixture of Moderation Experts (MoMoE), a modular, cross-community framework that adds post-hoc explanations to scalable content moderation. MoMoE orchestrates four operators -- Allocate, Predict, Aggregate, Explain -- and is instantiated as seven community-specialized experts (MoMoE-Community) and five norm-violation experts (MoMoE-NormVio). On 30 unseen subreddits, the best variants obtain Micro-F1 scores of 0.72 and 0.67, respectively, matching or surpassing strong fine-tuned baselines while consistently producing concise and reliable explanations. Although community-specialized experts deliver the highest peak accuracy, norm-violation experts provide steadier performance across domains. These findings show that MoMoE yields scalable, transparent moderation without needing per-community fine-tuning. More broadly, they suggest that lightweight, explainable expert ensembles can guide future NLP and HCI research on trustworthy human-AI governance of online communities.

[Arxiv](https://arxiv.org/abs/2505.14483)