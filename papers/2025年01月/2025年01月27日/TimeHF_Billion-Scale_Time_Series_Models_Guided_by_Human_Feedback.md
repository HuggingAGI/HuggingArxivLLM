# TimeHF: 人类反馈驱动的十亿级时间序列模型

发布时间：2025年01月27日

`LLM应用

理由：这篇论文讨论了受大型语言模型（LLM）启发，开发大型时间序列模型（LTM）以解决时间序列神经网络的可扩展性、泛化能力和零-shot性能等问题。论文提出的TimeHF流程结合了人类反馈机制，并在实际工业应用中展示了显著的性能提升。虽然论文主要关注时间序列模型，但其核心思想和方法受到了LLM的启发，并且在实际应用中展示了LLM技术的扩展和应用，因此归类为LLM应用。` `供应链` `时间序列分析`

> TimeHF: Billion-Scale Time Series Models Guided by Human Feedback

# 摘要

> 时间序列神经网络在现实应用中表现出色，但也面临可扩展性有限、泛化能力差和零-shot性能不佳等挑战。受大型语言模型的启发，业界开始探索开发大型时间序列模型（LTM）以解决这些问题。然而，现有方法在训练复杂性、适应人类反馈和实现高预测准确性方面仍有不足。我们提出了TimeHF，这是一个创新的流程，用于创建包含60亿参数并融入人类反馈的LTM。我们采用补丁卷积嵌入来捕捉长时间序列信息，并设计了一种名为时间序列策略优化的人类反馈机制。TimeHF已在京东供应链中部署，处理了超过20,000种产品的自动补货，预测准确性较现有方法提升了33.21%。这一成果不仅推动了LTM技术的发展，还展示了显著的工业应用价值。

> Time series neural networks perform exceptionally well in real-world applications but encounter challenges such as limited scalability, poor generalization, and suboptimal zero-shot performance. Inspired by large language models, there is interest in developing large time series models (LTM) to address these issues. However, current methods struggle with training complexity, adapting human feedback, and achieving high predictive accuracy. We introduce TimeHF, a novel pipeline for creating LTMs with 6 billion parameters, incorporating human feedback. We use patch convolutional embedding to capture long time series information and design a human feedback mechanism called time-series policy optimization. Deployed in JD.com's supply chain, TimeHF handles automated replenishment for over 20,000 products, improving prediction accuracy by 33.21% over existing methods. This work advances LTM technology and shows significant industrial benefits.

[Arxiv](https://arxiv.org/abs/2501.15942)