# 策略推导：利用增强记忆的可解释上下文学习预测初创企业成功

发布时间：2025年05月27日

`LLM应用` `投资决策`

> Policy Induction: Predicting Startup Success via Explainable Memory-Augmented In-Context Learning

# 摘要

> 早期创业投资风险极高，面临数据稀缺和结果高度不确定的双重挑战。传统的机器学习方法不仅需要大量标注数据和繁琐微调，还存在黑箱问题，难以让领域专家理解和改进。本文提出了一种基于增强记忆的大型语言模型（LLMs）结合上下文学习（ICL）的透明且数据高效的决策框架。我们的创新之处在于将自然语言策略直接嵌入LLM的提示中，使模型能够应用明确的推理模式，同时让人类专家能够轻松解释、审核并逐步优化决策逻辑。我们设计了一种轻量级训练流程，巧妙结合少量样本学习和上下文学习循环，使LLM能够根据结构化反馈逐步迭代优化决策策略。仅需极小监督且无需复杂的梯度优化，我们的系统对创业成功的预测准确度远超现有基准。其准确率比随机猜测高出20多倍（随机猜测成功率仅为1.9%），与顶级风投（VC）公司5.6%的典型成功率相比，准确率提升了7.1倍。


> Early-stage startup investment is a high-risk endeavor characterized by scarce data and uncertain outcomes. Traditional machine learning approaches often require large, labeled datasets and extensive fine-tuning, yet remain opaque and difficult for domain experts to interpret or improve. In this paper, we propose a transparent and data-efficient investment decision framework powered by memory-augmented large language models (LLMs) using in-context learning (ICL). Central to our method is a natural language policy embedded directly into the LLM prompt, enabling the model to apply explicit reasoning patterns and allowing human experts to easily interpret, audit, and iteratively refine the logic. We introduce a lightweight training process that combines few-shot learning with an in-context learning loop, enabling the LLM to update its decision policy iteratively based on structured feedback. With only minimal supervision and no gradient-based optimization, our system predicts startup success far more accurately than existing benchmarks. It is over 20x more precise than random chance, which succeeds 1.9% of the time. It is also 7.1x more precise than the typical 5.6% success rate of top-tier venture capital (VC) firms.

[Arxiv](https://arxiv.org/abs/2505.21427)