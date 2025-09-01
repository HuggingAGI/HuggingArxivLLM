# 提升航空安全分析水平：基于群体相对策略优化的强化学习HFACS分类自动化

发布时间：2025年08月28日

`强化学习` `交通运输`

> Improving Aviation Safety Analysis: Automated HFACS Classification Using Reinforcement Learning with Group Relative Policy Optimization

# 摘要

> 深入分析航空事故背后的人为因素是预防未来事故的关键，但传统基于人为因素分析与分类系统（HFACS）的方法在可扩展性和一致性方面存在局限。为此，我们提出了一个面向航空安全分析的自动化HFACS分类框架，该框架采用群体相对策略优化（GRPO）强化学习技术来微调Llama-3.1 8B语言模型。该方法融合了专为航空安全分析设计的多组件奖励机制，并集成合成数据生成技术以解决事故数据集中的类别不平衡难题。经GRPO优化后的模型性能显著提升，其中精确匹配准确率大幅提高350%（从0.0400升至0.1800），部分匹配准确率也达到0.8800。值得注意的是，我们的专用模型在关键指标上超越了GPT-5-mini和Gemini-2.5-fiash等当前最先进的大型语言模型（LLMs）。本研究还创新性地提出，将多标签HFACS分类任务中的精确匹配准确率作为评估语言模型高级推理能力的新基准。最后，本研究证实，小型化、领域优化的模型能够为关键安全分析提供计算高效且性能更优的解决方案。该方法还实现了在资源受限的边缘设备上进行高性能、低延迟部署的可行性。

> Analyzing the human factors behind aviation accidents is crucial for preventing future incidents, yet traditional methods using the Human Factors Analysis and Classification System (HFACS) are limited by scalability and consistency. To address this, we introduce an automated HFACS classification framework for aviation safety analysis that utilizes Reinforcement Learning with Group Relative Policy Optimization (GRPO) to fine-tune a Llama-3.1 8B language model. Our approach incorporates a multi-component reward system tailored for aviation safety analysis and integrates synthetic data generation to overcome class imbalance in accident datasets. The resulting GRPO-optimized model achieved noticeable performance gains, including a 350% increase in exact match accuracy (from 0.0400 to 0.1800) and an improved partial match accuracy of 0.8800. Significantly, our specialized model outperforms state-of-the-art LLMs (Large Language Models), including GPT-5-mini and Gemini-2.5-fiash, on key metrics. This research also proposes exact match accuracy in multi-label HFACS classification problem as a new benchmarking methodology to evaluate the advanced reasoning capabilities of language models. Ultimately, our work validates that smaller, domain-optimized models can provide a computationally efficient and better solution for critical safety analysis. This approach makes powerful, low-latency deployment on resource-constrained edge devices feasible.

[Arxiv](https://arxiv.org/abs/2508.21201)