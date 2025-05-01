# MAC-Tuning: 基于增强知识边界感知的 LLM 多组合式问题解决能力

发布时间：2025年04月30日

`LLM应用` `AI技术` `问答系统`

> MAC-Tuning: LLM Multi-Compositional Problem Reasoning with Enhanced Knowledge Boundary Awareness

# 摘要

> 随着大型语言模型（LLMs）的广泛应用，幻觉问题——生成不存在的事实——引起了越来越多的关注。以往研究主要集中在单一问题设置下提升 LLM 的置信度估计。然而，在更具挑战性的多问题设置下，LLM 对其内部参数化知识边界的认知仍鲜有探索，这种设置要求同时准确回答多个问题。为填补这一空白，我们提出了一种新方法，即多答案与置信度逐步微调（MAC-Tuning），该方法在基于指令数据的微调过程中分离了答案预测和置信度估计的学习。大量实验表明，我们的方法在平均精度上比基线方法高出 25%。

> With the widespread application of large language models (LLMs), the issue of generating non-existing facts, known as hallucination, has garnered increasing attention. Previous research in enhancing LLM confidence estimation mainly focuses on the single problem setting. However, LLM awareness of its internal parameterized knowledge boundary under the more challenging multi-problem setting, which requires answering multiple problems accurately simultaneously, remains underexplored. To bridge this gap, we introduce a novel method, Multiple Answers and Confidence Stepwise Tuning (MAC-Tuning), that separates the learning of answer prediction and confidence estimation during fine-tuning on instruction data. Extensive experiments demonstrate that our method outperforms baselines by up to 25% in average precision.

[Arxiv](https://arxiv.org/abs/2504.21773)