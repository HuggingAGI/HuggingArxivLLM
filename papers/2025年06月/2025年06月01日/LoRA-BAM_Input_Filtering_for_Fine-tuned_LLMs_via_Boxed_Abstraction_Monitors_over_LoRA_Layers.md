# LoRA-BAM：通过LoRA层上的盒式抽象监控器实现对微调后LLM的输入过滤

发布时间：2025年06月01日

`LLM应用` `人工智能` `机器学习`

> LoRA-BAM: Input Filtering for Fine-tuned LLMs via Boxed Abstraction Monitors over LoRA Layers

# 摘要

> 微调大型语言模型（LLMs）虽然能显著提升特定领域任务的性能，但也可能引发过拟合问题，导致模型在处理分布外（OoD）查询时表现不稳定。为此，我们提出了LoRA-BAM方法，通过在LoRA层中引入基于盒式抽象的分布外检测监控器，有效过滤超出模型能力范围的问题。具体而言，我们从微调数据中提取特征向量并进行聚类，将这些聚类结果包裹在盒中；若一个问题的特征向量位于所有盒子之外，则判定其为分布外。为了增强模型的可解释性和鲁棒性，我们在微调过程中引入了一种正则化损失，旨在保持相似问题在特征空间中的接近性，并依据簇内特征方差动态调整决策边界。我们的方法通过提供轻量级且易于解释的分布外检测机制，为现有的防御措施提供了重要补充。

> Fine-tuning large language models (LLMs) improves performance on domain-specific tasks but can lead to overfitting, making them unreliable on out-of-distribution (OoD) queries. We propose LoRA-BAM - a method that adds OoD detection monitors to the LoRA layer using boxed abstraction to filter questions beyond the model's competence. Feature vectors from the fine-tuning data are extracted via the LLM and clustered. Clusters are enclosed in boxes; a question is flagged as OoD if its feature vector falls outside all boxes. To improve interpretability and robustness, we introduce a regularization loss during fine-tuning that encourages paraphrased questions to stay close in the feature space, and the enlargement of the decision boundary is based on the feature variance within a cluster. Our method complements existing defenses by providing lightweight and interpretable OoD detection.

[Arxiv](https://arxiv.org/abs/2506.00998)