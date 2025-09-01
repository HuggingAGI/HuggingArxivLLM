# PiCSAR：概率置信度选择与排序

发布时间：2025年08月29日

`LLM应用` `基础理论`

> PiCSAR: Probabilistic Confidence Selection And Ranking

# 摘要

> n选优采样（Best-of-n sampling）通过生成多个候选解并选取奖励最高的方案，有效提升了大型语言模型（LLMs）和大型推理模型（LRMs）的准确率。推理任务的核心挑战在于设计一种评分函数，使其在无法获取真实答案（ground-truth answers）时仍能识别正确的推理链。为此，我们提出概率置信选择与排序（Probabilistic Confidence Selection And Ranking，PiCSAR）：这是一种简单且无需训练的方法，通过推理过程与最终答案的联合对数似然对每个候选生成结果进行评分。该联合对数似然可自然分解为推理置信度和答案置信度两部分。PiCSAR在多个基准测试中均实现显著性能提升（MATH500提升10.18，AIME2025提升9.81），且在20次对比实验中有16次仅用至少一半的样本量就超越了基线模型。我们的分析进一步发现，正确的推理链往往具有显著更高的推理置信度和答案置信度，这也印证了PiCSAR的有效性。

> Best-of-n sampling improves the accuracy of large language models (LLMs) and large reasoning models (LRMs) by generating multiple candidate solutions and selecting the one with the highest reward. The key challenge for reasoning tasks is designing a scoring function that can identify correct reasoning chains without access to ground-truth answers. We propose Probabilistic Confidence Selection And Ranking (PiCSAR): a simple, training-free method that scores each candidate generation using the joint log-likelihood of the reasoning and final answer. The joint log-likelihood of the reasoning and final answer naturally decomposes into reasoning confidence and answer confidence. PiCSAR achieves substantial gains across diverse benchmarks (+10.18 on MATH500, +9.81 on AIME2025), outperforming baselines with at least 2x fewer samples in 16 out of 20 comparisons. Our analysis reveals that correct reasoning chains exhibit significantly higher reasoning and answer confidence, justifying the effectiveness of PiCSAR.

[Arxiv](https://arxiv.org/abs/2508.21787)