# NeuroGen：利用大型语言模型生成神经网络参数

发布时间：2025年05月18日

`LLM应用

理由：这篇论文探讨了如何利用大语言模型（LLM）生成神经网络参数，提出了一种称为NeuroGen的两阶段方法。研究的核心在于应用大语言模型来解决参数生成问题，展示了LLM在这一特定任务中的应用潜力，并提出了一种新的范式，即LLM与轻量级神经网络的协同工作。因此，这篇论文属于LLM应用类别，因为它专注于将LLM应用于生成神经网络参数这一具体任务中。` `机器学习`

> NeuroGen: Neural Network Parameter Generation via Large Language Models

# 摘要

> 自神经网络诞生以来，获取网络参数一直是机器学习领域的核心问题。传统方法如反向传播和前向优化通过迭代拟合数据逐步优化参数。本文提出了一种新思路：利用大语言模型生成神经网络参数。我们开发了NeuroGen，这是一种通用且易于实现的两阶段方法，可根据数据、任务和网络架构生成网络参数。第一阶段是参数参考知识注入，通过在神经网络检查点上预训练大语言模型，使其建立对参数空间的基础理解；第二阶段是上下文增强指令微调，使模型能够通过任务感知提示适应特定任务。实验结果表明，NeuroGen能有效生成可用的神经网络参数。我们的研究展示了基于大语言模型的参数生成的可行性，并提出了一种全新范式：大语言模型与轻量级神经网络协同共存。

> Acquiring the parameters of neural networks (NNs) has been one of the most important problems in machine learning since the inception of NNs. Traditional approaches, such as backpropagation and forward-only optimization, acquire parameters via iterative data fitting to gradually optimize them. This paper aims to explore the feasibility of a new direction: acquiring NN parameters via large language model generation. We propose NeuroGen, a generalized and easy-to-implement two-stage approach for NN parameter generation conditioned on descriptions of the data, task, and network architecture. Stage one is Parameter Reference Knowledge Injection, where LLMs are pretrained on NN checkpoints to build foundational understanding of parameter space, whereas stage two is Context-Enhanced Instruction Tuning, enabling LLMs to adapt to specific tasks through enriched, task-aware prompts. Experimental results demonstrate that NeuroGen effectively generates usable NN parameters. Our findings highlight the feasibility of LLM-based NN parameter generation and suggest a promising new paradigm where LLMs and lightweight NNs can coexist synergistically

[Arxiv](https://arxiv.org/abs/2505.12470)