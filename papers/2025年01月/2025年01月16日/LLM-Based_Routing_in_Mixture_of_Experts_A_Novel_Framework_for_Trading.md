# 基于LLM的专家混合路由：创新交易框架

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要讨论的是如何利用大语言模型（LLMs）来改进专家混合（MoE）机制在股票投资领域的应用。具体来说，论文提出了一种新的框架LLMoE，利用LLMs作为路由器来筛选专家，从而提升选择机制的有效性和可解释性。这表明论文的核心是将LLMs应用于特定的实际问题（股票投资），因此应归类为LLM应用。` `股票投资`

> LLM-Based Routing in Mixture of Experts: A Novel Framework for Trading

# 摘要

> # 摘要
深度学习与大语言模型（LLMs）的突破性进展，推动了专家混合（MoE）机制在股票投资领域的应用。尽管这些模型在交易表现上展现出潜力，但它们往往局限于单一模态，忽视了文本数据等多模态信息的丰富性。此外，传统的神经网络路由选择机制未能充分考虑上下文和现实世界的复杂性，导致专家选择不尽如人意。为此，我们提出了LLMoE，一种创新框架，将LLMs作为MoE架构中的路由器。具体而言，我们摒弃了传统的神经网络路由器，转而利用LLMs的广泛知识库和推理能力，基于历史价格数据和股票新闻来筛选专家。这一方法不仅提升了选择机制的有效性，还增强了其可解释性。我们在多模态现实股票数据集上的实验表明，LLMoE在性能上超越了现有的MoE模型及其他深度神经网络方法。此外，LLMoE的灵活架构使其能够轻松应对各种下游任务。

> Recent advances in deep learning and large language models (LLMs) have facilitated the deployment of the mixture-of-experts (MoE) mechanism in the stock investment domain. While these models have demonstrated promising trading performance, they are often unimodal, neglecting the wealth of information available in other modalities, such as textual data. Moreover, the traditional neural network-based router selection mechanism fails to consider contextual and real-world nuances, resulting in suboptimal expert selection. To address these limitations, we propose LLMoE, a novel framework that employs LLMs as the router within the MoE architecture. Specifically, we replace the conventional neural network-based router with LLMs, leveraging their extensive world knowledge and reasoning capabilities to select experts based on historical price data and stock news. This approach provides a more effective and interpretable selection mechanism. Our experiments on multimodal real-world stock datasets demonstrate that LLMoE outperforms state-of-the-art MoE models and other deep neural network approaches. Additionally, the flexible architecture of LLMoE allows for easy adaptation to various downstream tasks.

[Arxiv](https://arxiv.org/abs/2501.09636)