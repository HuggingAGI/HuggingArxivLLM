# 大型语言模型在机械设计领域的有效性研究

发布时间：2025年05月02日

`LLM应用` `机械工程`

> On the effectiveness of Large Language Models in the mechanical design domain

# 摘要

> 本研究致力于探索大型语言模型在机械工程领域的性能。我们采用ABC数据集中的语义数据，包括设计师为整体装配体命名的组件名称，以及为每个零件分配的语义部件名称。通过数据预处理，我们设计了两个无监督任务来评估不同模型架构在领域数据上的表现：二分类句对分类任务和零样本分类任务。针对二分类任务，我们通过微调模型来对抗过拟合，包括调整学习率、修改dropout值、优化序列长度以及添加多头注意力层，最终达到了0.62的准确率。在零样本分类任务中，我们的模型表现远超基线，实现了0.386的Top-1分类准确率。这些结果揭示了在该领域进行语言学习时可能出现的具体失败模式，为模型优化提供了重要参考。

> In this work, we seek to understand the performance of large language models in the mechanical engineering domain. We leverage the semantic data found in the ABC dataset, specifically the assembly names that designers assigned to the overall assemblies, and the individual semantic part names that were assigned to each part. After pre-processing the data we developed two unsupervised tasks to evaluate how different model architectures perform on domain-specific data: a binary sentence-pair classification task and a zero-shot classification task. We achieved a 0.62 accuracy for the binary sentence-pair classification task with a fine-tuned model that focuses on fighting over-fitting: 1) modifying learning rates, 2) dropout values, 3) Sequence Length, and 4) adding a multi-head attention layer. Our model on the zero-shot classification task outperforms the baselines by a wide margin, and achieves a top-1 classification accuracy of 0.386. The results shed some light on the specific failure modes that arise when learning from language in this domain.

[Arxiv](https://arxiv.org/abs/2505.01559)