# 知识驱动的多模态心电图表示学习：支持任意导联输入

发布时间：2025年02月25日

`LLM应用` `医学影像分析`

> Knowledge-enhanced Multimodal ECG Representation Learning with Arbitrary-Lead Inputs

# 摘要

> 多模态心电图表示学习的最新研究重点在于将心电图信号与自由文本报告进行对齐。然而，由于医学语言的复杂性和对完整12导联数据的依赖，这种对齐方式仍存在不足，特别是在资源有限的场景下。针对这些挑战，我们提出了一种名为**K-MERL**的知识增强型多模态心电图表示学习框架。该框架通过大型语言模型从自由文本报告中提取结构化知识，并采用一种支持动态导联遮罩的导联感知ECG编码器，以适应任意导联输入。实验结果表明，在六项外部心电图数据集上，**K-MERL**不仅在零样本分类和线性探测任务中达到了当前最优性能，还在部分导联零样本分类任务中实现了相比现有方法平均**16%**的AUC提升，展现出显著优势。

> Recent advances in multimodal ECG representation learning center on aligning ECG signals with paired free-text reports. However, suboptimal alignment persists due to the complexity of medical language and the reliance on a full 12-lead setup, which is often unavailable in under-resourced settings. To tackle these issues, we propose **K-MERL**, a knowledge-enhanced multimodal ECG representation learning framework. **K-MERL** leverages large language models to extract structured knowledge from free-text reports and employs a lead-aware ECG encoder with dynamic lead masking to accommodate arbitrary lead inputs. Evaluations on six external ECG datasets show that **K-MERL** achieves state-of-the-art performance in zero-shot classification and linear probing tasks, while delivering an average **16%** AUC improvement over existing methods in partial-lead zero-shot classification.

[Arxiv](https://arxiv.org/abs/2502.17900)