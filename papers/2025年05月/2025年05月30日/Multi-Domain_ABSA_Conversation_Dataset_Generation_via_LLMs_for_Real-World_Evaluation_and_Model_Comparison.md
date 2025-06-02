# # 多领域 ABSA 对话数据集生成  
通过大语言模型生成多领域 ABSA 对话数据集，助力现实世界评估与模型对比

发布时间：2025年05月30日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型生成合成数据用于基于方面的情感分析（ABSA），属于LLM在特定任务中的应用，因此归类为LLM应用。` `数据生成`

> Multi-Domain ABSA Conversation Dataset Generation via LLMs for Real-World Evaluation and Model Comparison

# 摘要

> 基于方面的情感分析（ABSA）能够提供细致的意见洞察，但常常面临缺乏多样化的、反映现实对话细微差别且带有标注的数据集这一问题。本文提出了一种利用大型语言模型（LLMs）生成合成ABSA数据的方法，以填补这一空白。我们详细介绍了旨在通过GPT-4o生成多领域数据的过程，确保主题和情感分布的一致性。通过评估三个最先进LLMs（Gemini 1.5 Pro、Claude 3.5 Sonnet和DeepSeek-R1）在主题和情感分类任务上的表现，我们验证了生成数据的质量和实用性。实验结果表明，合成数据具有有效性，揭示了各模型之间的性能权衡：DeepSeekR1表现出更高的精确度，Gemini 1.5 Pro和Claude 3.5 Sonnet展现了强大的召回率，而Gemini 1.5 Pro则提供了显著更快的推理速度。我们得出结论，基于LLMs的合成数据生成是一种可行且灵活的方法，能够为ABSA研究和模型评估创造有价值的资源，而无需依赖有限或难以获取的真实标注数据。

> Aspect-Based Sentiment Analysis (ABSA) offers granular insights into opinions but often suffers from the scarcity of diverse, labeled datasets that reflect real-world conversational nuances. This paper presents an approach for generating synthetic ABSA data using Large Language Models (LLMs) to address this gap. We detail the generation process aimed at producing data with consistent topic and sentiment distributions across multiple domains using GPT-4o. The quality and utility of the generated data were evaluated by assessing the performance of three state-of-the-art LLMs (Gemini 1.5 Pro, Claude 3.5 Sonnet, and DeepSeek-R1) on topic and sentiment classification tasks. Our results demonstrate the effectiveness of the synthetic data, revealing distinct performance trade-offs among the models: DeepSeekR1 showed higher precision, Gemini 1.5 Pro and Claude 3.5 Sonnet exhibited strong recall, and Gemini 1.5 Pro offered significantly faster inference. We conclude that LLM-based synthetic data generation is a viable and flexible method for creating valuable ABSA resources, facilitating research and model evaluation without reliance on limited or inaccessible real-world labeled data.

[Arxiv](https://arxiv.org/abs/2505.24701)