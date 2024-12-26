# 高效且具备上下文感知的标签传播，用于视觉语言模型零/少样本的无训练自适应

发布时间：2024年12月24日

`LLM应用` `机器学习` `视觉语言模型`

> Efficient and Context-Aware Label Propagation for Zero-/Few-Shot Training-Free Adaptation of Vision-Language Model

# 摘要

> 视觉语言模型（VLMs）借助大型预训练模型处理各类下游任务，给机器学习带来了革命性变化。尽管在标签、训练及数据效率上有所提升，但不少顶尖的 VLMs 仍需针对任务进行超参数调整，且未能充分利用测试样本。为应对这些难题，我们提出一种基于图的标签高效适配与推理方法。该方法在文本提示、少量样本示例及测试样本上动态构建图，利用标签传播进行推理，无需针对特定任务进行调整。与现有的零样本标签传播技术不同，我们的方法无需额外的未标记支持集，通过动态图扩展有效利用测试样本流形。我们还引入了上下文感知特征重加权机制，以提高任务适配的准确性。此外，我们的方法支持高效的图扩展，能够实现实时归纳推理。对下游任务（如细粒度分类和分布外泛化）的大量评估表明了我们方法的有效性。

> Vision-language models (VLMs) have revolutionized machine learning by leveraging large pre-trained models to tackle various downstream tasks. Despite improvements in label, training, and data efficiency, many state-of-the-art VLMs still require task-specific hyperparameter tuning and fail to fully exploit test samples. To overcome these challenges, we propose a graph-based approach for label-efficient adaptation and inference. Our method dynamically constructs a graph over text prompts, few-shot examples, and test samples, using label propagation for inference without task-specific tuning. Unlike existing zero-shot label propagation techniques, our approach requires no additional unlabeled support set and effectively leverages the test sample manifold through dynamic graph expansion. We further introduce a context-aware feature re-weighting mechanism to improve task adaptation accuracy. Additionally, our method supports efficient graph expansion, enabling real-time inductive inference. Extensive evaluations on downstream tasks, such as fine-grained categorization and out-of-distribution generalization, demonstrate the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2412.18303)