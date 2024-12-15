# Dial-In LLM: 采用 LLM 循环的与人类对齐的对话意图聚类

发布时间：2024年12月12日

`LLM应用` `自动化` `客户服务`

> Dial-In LLM: Human-Aligned Dialogue Intent Clustering with LLM-in-the-loop

# 摘要

> 在自动化支持系统中，从对话中探寻客户意图至关重要。然而，由于从嵌入距离转向语义距离，传统文本聚类方法与人类感知契合度欠佳，现有的文本聚类定量指标或许难以精准反映意图聚类的真实质量。本文借助大型语言模型（LLMs）出色的语言理解能力，设计出校准更优的意图聚类算法。我们首先通过验证微调后的LLM在语义一致性评估和聚类命名方面的效用稳健性来奠定基础，与人工标注的真实情况相比，准确率分别达97.50％和94.40％。接着，我们提出一种迭代聚类算法，利于聚类层级的优化以及高质量意图聚类的持续发掘。此外，我们还推出了若干针对从客户服务对话中发现意图的LLM循环半监督聚类技术。在涵盖1,507个意图聚类的大规模工业数据集上开展的实验，证实了所提技术的有效性。这些方法优于现有同类方法，构建意图分类器时，定量指标提升了6.25％，应用级性能提高了12％。

> The discovery of customer intention from dialogue plays an important role in automated support system. However, traditional text clustering methods are poorly aligned with human perceptions due to the shift from embedding distance to semantic distance, and existing quantitative metrics for text clustering may not accurately reflect the true quality of intent clusters. In this paper, we leverage the superior language understanding capabilities of Large Language Models (LLMs) for designing better-calibrated intent clustering algorithms. We first establish the foundation by verifying the robustness of fine-tuned LLM utility in semantic coherence evaluation and cluster naming, resulting in an accuracy of 97.50% and 94.40%, respectively, when compared to the human-labeled ground truth. Then, we propose an iterative clustering algorithm that facilitates cluster-level refinement and the continuous discovery of high-quality intent clusters. Furthermore, we present several LLM-in-the-loop semi-supervised clustering techniques tailored for intent discovery from customer service dialogue. Experiments on a large-scale industrial dataset comprising 1,507 intent clusters demonstrate the effectiveness of the proposed techniques. The methods outperformed existing counterparts, achieving 6.25% improvement in quantitative metrics and 12% enhancement in application-level performance when constructing an intent classifier.

[Arxiv](https://arxiv.org/abs/2412.09049)