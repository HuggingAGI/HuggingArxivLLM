# # 注意力头的分类方法：加速联邦PEFT的剪枝与策略化客户端选择

发布时间：2025年05月31日

`LLM应用

理由：这篇论文探讨了参数高效微调（PEFT）在联邦学习框架中的应用，特别是在多头注意力语言模型上的优化方法。它属于将大型语言模型应用于特定任务和场景，因此归类为LLM应用。` `联邦学习`

> Assortment of Attention Heads: Accelerating Federated PEFT with Head Pruning and Strategic Client Selection

# 摘要

> 参数高效微调（PEFT）已经成为自然语言处理领域中对大型语言模型（LLMs）进行下游任务适应的事实上的标准方法。然而，其在隐私保护的分布式学习框架（如联邦学习（FL））中的应用仍然相对有限。这主要是由于联邦学习中特有的挑战，例如资源受限的设备和客户端之间数据分布的多样性。本文中，我们提出了一种在联邦学习框架内对基于多头注意力（MHA）的语言模型进行PEFT的高效方法。我们通过头部剪枝、一种新颖的头特定加权聚合机制以及客户端选择策略来解决这些挑战。头部剪枝通过基于注意力头置信度计算的重要性评分，在客户端内最小化训练复杂度。头部的加权聚合确保全局模型能够捕捉到来自不同客户端的关键更新，这与我们的客户端选择策略相辅相成。我们在MultiNLI基准测试以及20 Newsgroups、XL-Sum和E2E NLG数据集上展示了实验结果。我们使用MultiNLI数据集和T5-small模型，结合LoRA作为PEFT方法，实现了高达90%的稀疏性，同时在保持精度下降不超过2%的情况下，通信效率提升了1.8倍，训练运算量减少了3.9倍。

> Parameter Efficient Fine-Tuning (PEFT) has become the de-facto approach in adapting Large Language Models (LLMs) for downstream tasks in Natural Language Processing. However, its adoption in privacy-preserving distributed learning frameworks, such as Federated Learning (FL), remains relatively limited. This is mainly due to challenges specific to FL, such as resource-constrained devices and diverse data distributions among clients. In this paper, we propose an efficient method to perform PEFT within the FL framework for Multi-Head Attention (MHA) based language models. We address the challenges through head pruning, a novel head-specific weighted aggregation mechanism, and a client selection strategy. Head pruning minimizes training complexity within the clients, guided by the importance score computed based on the confidence of the attention head. Weighted aggregation of heads ensures the global model captures crucial updates from diverse clients complementing our client selection strategy. We show results on the MultiNLI benchmark along with 20 Newsgroups, XL-Sum, and E2E NLG datasets. We use the MultiNLI dataset and T5-small model with LoRA as our PEFT method, attaining sparsity levels of up to 90%, resulting in a communication advantage of up to 1.8x and a reduction in training OPs of 3.9x while maintaining the accuracy drop under 2%.

[Arxiv](https://arxiv.org/abs/2506.00743)