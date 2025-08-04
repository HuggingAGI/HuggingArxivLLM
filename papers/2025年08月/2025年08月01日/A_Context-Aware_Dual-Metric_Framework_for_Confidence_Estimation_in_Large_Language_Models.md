# 上下文感知双指标框架：大型语言模型的置信度估计

发布时间：2025年08月01日

`LLM理论` `问答系统` `关键安全应用`

> A Context-Aware Dual-Metric Framework for Confidence Estimation in Large Language Models

# 摘要

> 准确的信心估计对于可信的大型语言模型 (LLMs) 系统至关重要，因为它赋予用户决定何时信任输出的能力，并使在关键安全应用中的可靠部署成为可能。当前针对 LLMs 的信心估计方法忽略了响应与上下文信息之间的相关性，这一因素在输出质量评估中至关重要，尤其是在提供背景知识的场景中。为了解决这一问题，我们提出 CRUX（上下文感知的熵减少和统一一致性检查），这是首个通过两个新颖指标将上下文忠实性和一致性整合起来进行信心估计的框架。首先，上下文熵减少通过对比采样（有上下文和无上下文）来表示数据不确定性，利用信息增益进行衡量。其次，统一一致性检查通过生成答案与上下文相关性和无关性的一致性，捕捉潜在的模型不确定性。在三个基准数据集（CoQA、SQuAD、QuAC）和两个领域特定数据集（BioASQ、EduQG）上的实验验证了 CRUX 的有效性，其 AUROC 值高于现有基线模型。

> Accurate confidence estimation is essential for trustworthy large language models (LLMs) systems, as it empowers the user to determine when to trust outputs and enables reliable deployment in safety-critical applications. Current confidence estimation methods for LLMs neglect the relevance between responses and contextual information, a crucial factor in output quality evaluation, particularly in scenarios where background knowledge is provided. To bridge this gap, we propose CRUX (Context-aware entropy Reduction and Unified consistency eXamination), the first framework that integrates context faithfulness and consistency for confidence estimation via two novel metrics. First, contextual entropy reduction represents data uncertainty with the information gain through contrastive sampling with and without context. Second, unified consistency examination captures potential model uncertainty through the global consistency of the generated answers with and without context. Experiments across three benchmark datasets (CoQA, SQuAD, QuAC) and two domain-specific datasets (BioASQ, EduQG) demonstrate CRUX's effectiveness, achieving the highest AUROC than existing baselines.

[Arxiv](https://arxiv.org/abs/2508.00600)