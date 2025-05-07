# 无学习 vs. 模糊化：我们真的在移除知识吗？

发布时间：2025年05月05日

`LLM理论` `AI伦理` `隐私保护`

> Unlearning vs. Obfuscation: Are We Truly Removing Knowledge?

# 摘要

> 遗忘能力已成为大型语言模型（LLMs）实现数据隐私保护、合规性要求及伦理化AI部署的关键技术。当前主流方法通过注入错误或不相关信息来混淆知识，但这本质上是知识添加而非真正移除，容易导致模型被探测攻击。本文正式区分了遗忘与混淆概念，并提出基于探测的评估框架，用于检验现有方法是否真正移除了目标信息。我们还提出了DF-MCQ这一创新方法，通过KL散度在自动生成的多项选择题上平坦化模型预测分布，有效消除目标个体知识并触发适当拒绝行为。实验结果表明，DF-MCQ实现了卓越的遗忘效果，拒绝率超过90%，且在探测问题上的不确定性水平远超传统混淆方法，接近随机选择级别。

> Unlearning has emerged as a critical capability for large language models (LLMs) to support data privacy, regulatory compliance, and ethical AI deployment. Recent techniques often rely on obfuscation by injecting incorrect or irrelevant information to suppress knowledge. Such methods effectively constitute knowledge addition rather than true removal, often leaving models vulnerable to probing. In this paper, we formally distinguish unlearning from obfuscation and introduce a probing-based evaluation framework to assess whether existing approaches genuinely remove targeted information. Moreover, we propose DF-MCQ, a novel unlearning method that flattens the model predictive distribution over automatically generated multiple-choice questions using KL-divergence, effectively removing knowledge about target individuals and triggering appropriate refusal behaviour. Experimental results demonstrate that DF-MCQ achieves unlearning with over 90% refusal rate and a random choice-level uncertainty that is much higher than obfuscation on probing questions.

[Arxiv](https://arxiv.org/abs/2505.02884)