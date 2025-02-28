# 大型语言模型：高效模型训练的可解释性正则化器

发布时间：2025年02月27日

`LLM应用` `模型压缩`

> Large Language Models as Attribution Regularizers for Efficient Model Training

# 摘要

> 大型语言模型（LLMs）在各个领域都展现出了卓越的表现。然而，如何有效利用其丰富的知识来训练更小的下游模型仍然是一个开放性挑战，尤其是在表格数据学习等需要更简单模型（因其可解释性和效率）的领域。
    本文提出了一种新颖且简单的方法，将LLM生成的全局任务特征属性整合到小网络的训练过程中。具体来说，我们提出了一种归因匹配正则化项，使小模型的训练动态与LLM提供的见解保持一致。通过这种方法，我们在少量样本学习场景中取得了更优的性能。
    值得一提的是，我们的方法仅需对LLM进行黑盒API访问，即可轻松集成到现有训练流程中，且计算开销极小。此外，我们展示了如何利用此方法解决实际数据集中的常见问题，如偏斜和偏差。通过整合LLMs的高层知识，即使在训练数据有限或不平衡的情况下，我们的方法也能提升模型的泛化能力。
    通过在多个任务上的广泛实验，我们验证了该方法的有效性，展现了其在学习效率和模型鲁棒性方面的提升。

> Large Language Models (LLMs) have demonstrated remarkable performance across diverse domains. However, effectively leveraging their vast knowledge for training smaller downstream models remains an open challenge, especially in domains like tabular data learning, where simpler models are often preferred due to interpretability and efficiency.
  In this paper, we introduce a novel yet straightforward method for incorporating LLM-generated global task feature attributions into the training process of smaller networks. Specifically, we propose an attribution-matching regularization term that aligns the training dynamics of the smaller model with the insights provided by the LLM. By doing so, our approach yields superior performance in few-shot learning scenarios. Notably, our method requires only black-box API access to the LLM, making it easy to integrate into existing training pipelines with minimal computational overhead.
  Furthermore, we demonstrate how this method can be used to address common issues in real-world datasets, such as skewness and bias. By integrating high-level knowledge from LLMs, our approach improves generalization, even when training data is limited or imbalanced. We validate its effectiveness through extensive experiments across multiple tasks, demonstrating improved learning efficiency and model robustness.

[Arxiv](https://arxiv.org/abs/2502.20268)