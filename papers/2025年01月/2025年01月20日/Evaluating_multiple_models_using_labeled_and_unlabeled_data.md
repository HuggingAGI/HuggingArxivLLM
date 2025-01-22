# 利用标注与未标注数据评估多模型性能

发布时间：2025年01月20日

`其他

理由：这篇论文主要讨论的是在没有大量标注数据的情况下评估机器学习分类器的方法，提出了半监督模型评估（SSME）的方法。虽然提到了语言模型性能的评估，但核心内容并不直接涉及大型语言模型（LLM）的理论、应用、Agent或RAG（Retrieval-Augmented Generation）技术。因此，将其分类为“其他”更为合适。` `医疗保健` `内容审核`

> Evaluating multiple models using labeled and unlabeled data

# 摘要

> 在没有大量标注数据的情况下，评估机器学习分类器仍然具有挑战性。虽然标注数据可能昂贵或难以获取，但未标注数据却非常丰富。我们提出了一种名为半监督模型评估（SSME）的方法，它结合标注和未标注数据来评估分类器。SSME 是首个利用以下优势的评估方法：（i）同一任务通常有多个分类器，（ii）所有类别的分类器分数通常可用，（iii）未标注数据远多于标注数据。其核心思想是通过半监督混合模型估计真实标签和分类器预测的联合分布，从而计算基于分类器分数和真实标签的指标（如准确率或预期校准误差）。我们在四个难以获取大量标注数据的领域进行了实验：（1）医疗保健，（2）内容审核，（3）分子属性预测，以及（4）图像标注。实验结果表明，SSME 比现有方法更准确地估计性能，误差比仅使用标注数据减少了 5.1 倍，比次优方法减少了 2.4 倍。此外，SSME 在评估测试分布子集（如特定人口统计子组）和语言模型性能时，也显著提升了准确性。

> It remains difficult to evaluate machine learning classifiers in the absence of a large, labeled dataset. While labeled data can be prohibitively expensive or impossible to obtain, unlabeled data is plentiful. Here, we introduce Semi-Supervised Model Evaluation (SSME), a method that uses both labeled and unlabeled data to evaluate machine learning classifiers. SSME is the first evaluation method to take advantage of the fact that: (i) there are frequently multiple classifiers for the same task, (ii) continuous classifier scores are often available for all classes, and (iii) unlabeled data is often far more plentiful than labeled data. The key idea is to use a semi-supervised mixture model to estimate the joint distribution of ground truth labels and classifier predictions. We can then use this model to estimate any metric that is a function of classifier scores and ground truth labels (e.g., accuracy or expected calibration error). We present experiments in four domains where obtaining large labeled datasets is often impractical: (1) healthcare, (2) content moderation, (3) molecular property prediction, and (4) image annotation. Our results demonstrate that SSME estimates performance more accurately than do competing methods, reducing error by 5.1x relative to using labeled data alone and 2.4x relative to the next best competing method. SSME also improves accuracy when evaluating performance across subsets of the test distribution (e.g., specific demographic subgroups) and when evaluating the performance of language models.

[Arxiv](https://arxiv.org/abs/2501.11866)