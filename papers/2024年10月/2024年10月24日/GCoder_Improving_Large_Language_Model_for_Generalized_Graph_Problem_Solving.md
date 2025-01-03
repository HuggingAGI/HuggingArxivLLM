# GCoder: 增强大型语言模型在通用图问题求解中的能力

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来解决图计算问题，并提出了一个名为GCoder的基于代码的LLM。论文的重点在于如何通过训练和优化LLM来提升其在图计算任务中的表现，并展示了其在处理大规模图数据时的优势。这属于LLM在实际应用中的具体使用场景，因此归类为“LLM应用”。` `图计算` `人工智能`

> GCoder: Improving Large Language Model for Generalized Graph Problem Solving

# 摘要

> # 摘要
大型语言模型（LLMs）展现出强大的推理能力，适用于复杂任务如图计算。传统图问题推理步骤范式存在不可验证步骤、长期推理能力有限及对图变化泛化能力差等问题。为突破这些限制，我们推出GCoder，一个基于代码的LLM，旨在提升广义图计算问题的解决能力。我们构建了包含多样化图格式和算法的训练数据集GraphWild，并采用多阶段训练过程，包括监督微调（SFT）和从编译器反馈的强化学习（RLCF），以优化模型性能。对于未见任务，采用混合检索技术提升表现。实验显示，GCoder在各种图计算问题上的平均准确率比GPT-4o高出16.42%。此外，GCoder能高效处理数百万节点及多样化输入格式的大规模图，克服了以往模型在推理步骤范式上的局限。这一进展为LLMs在图问题解决上的应用开辟了更直观有效的路径。代码和数据可在此获取：https://github.com/Bklight999/WWW25-GCoder/tree/master。

> Large Language Models (LLMs) have demonstrated strong reasoning abilities, making them suitable for complex tasks such as graph computation. Traditional reasoning steps paradigm for graph problems is hindered by unverifiable steps, limited long-term reasoning, and poor generalization to graph variations. To overcome these limitations, we introduce GCoder, a code-based LLM designed to enhance problem-solving in generalized graph computation problems. Our method involves constructing an extensive training dataset, GraphWild, featuring diverse graph formats and algorithms. We employ a multi-stage training process, including Supervised Fine-Tuning (SFT) and Reinforcement Learning from Compiler Feedback (RLCF), to refine model capabilities. For unseen tasks, a hybrid retrieval technique is used to augment performance. Experiments demonstrate that GCoder outperforms GPT-4o, with an average accuracy improvement of 16.42% across various graph computational problems. Furthermore, GCoder efficiently manages large-scale graphs with millions of nodes and diverse input formats, overcoming the limitations of previous models focused on the reasoning steps paradigm. This advancement paves the way for more intuitive and effective graph problem-solving using LLMs. Code and data are available at here: https://github.com/Bklight999/WWW25-GCoder/tree/master.

[Arxiv](https://arxiv.org/abs/2410.19084)