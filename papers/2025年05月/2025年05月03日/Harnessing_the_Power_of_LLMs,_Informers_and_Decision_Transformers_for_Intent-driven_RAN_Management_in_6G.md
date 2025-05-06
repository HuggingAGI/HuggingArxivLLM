# 驾驭大型语言模型、信息增强器与决策转换器的力量，实现意图驱动的6G无线接入网管理

发布时间：2025年05月03日

`LLM应用` `人工智能`

> Harnessing the Power of LLMs, Informers and Decision Transformers for Intent-driven RAN Management in 6G

# 摘要

> 意图驱动的网络管理对于应对5G和6G网络的复杂性至关重要。它支持网络运营商根据自身目标进行自适应的按需网络管理。本文中，我们提出了一种基于生成式AI（GenAI）算法的创新三步框架用于意图驱动的网络管理。首先，我们使用量化低秩适配器（QLoRA）在自定义数据集上微调大型语言模型（LLM），以便在有限的计算资源内实现内存高效的意图处理。同时，我们引入了一个基于检索增强生成（RAG）的模块来支持动态决策。其次，我们采用一种基于Transformer架构的时间序列预测方法，用于预测关键参数（如功耗、流量负载和丢包率），从而实现主动的意图验证。最后，我们提出了一种带有目标感知的分层决策转换器（HDTGA），以优化网络应用的选择和编排，从而提升网络性能。我们的意图引导和处理方法相较于基础LLM模型，在BERTScore上提升了6%，语义相似度评分提高了9%。此外，我们提出的预测性意图验证方法能够以平均88%的准确率成功排除性能下降的意图。最后，与基线方法相比，我们提出的HDTGA算法至少将吞吐量提升了19.3%，延迟降低了48.5%，能效提升了54.9%。

> Intent-driven network management is critical for managing the complexity of 5G and 6G networks. It enables adaptive, on-demand management of the network based on the objectives of the network operators. In this paper, we propose an innovative three-step framework for intent-driven network management based on Generative AI (GenAI) algorithms. First, we fine-tune a Large Language Model (LLM) on a custom dataset using a Quantized Low-Rank Adapter (QLoRA) to enable memory-efficient intent processing within limited computational resources. A Retrieval Augmented Generation (RAG) module is included to support dynamic decision-making. Second, we utilize a transformer architecture for time series forecasting to predict key parameters, such as power consumption, traffic load, and packet drop rate, to facilitate intent validation proactively. Lastly, we introduce a Hierarchical Decision Transformer with Goal Awareness (HDTGA) to optimize the selection and orchestration of network applications and hence, optimize the network. Our intent guidance and processing approach improves BERTScore by 6% and the semantic similarity score by 9% compared to the base LLM model. Again, the proposed predictive intent validation approach can successfully rule out the performance-degrading intents with an average of 88% accuracy. Finally, compared to the baselines, the proposed HDTGA algorithm increases throughput at least by 19.3%, reduces delay by 48.5%, and boosts energy efficiency by 54.9%.

[Arxiv](https://arxiv.org/abs/2505.01841)