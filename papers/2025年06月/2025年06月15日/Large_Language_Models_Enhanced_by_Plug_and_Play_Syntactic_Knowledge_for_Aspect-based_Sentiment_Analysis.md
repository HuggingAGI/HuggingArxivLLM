# 即插即用句法知识赋能大型语言模型，提升基于方面的情感分析效果

发布时间：2025年06月15日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用到基于方面的意见挖掘（ABSA）任务中，提出了一种即插即用的方法，以最小的努力将LLMs适配到该任务。论文主要关注LLMs在特定任务中的应用和优化，因此属于LLM应用类别。`

> Large Language Models Enhanced by Plug and Play Syntactic Knowledge for Aspect-based Sentiment Analysis

# 摘要

> 基于方面的意见挖掘（ABSA）需要对上下文信息进行深入理解，包括与方面项相关的词语及其句法依存关系。现有研究多采用先进的编码器（如预训练模型，尤其是大型语言模型（LLMs））来捕捉此类上下文。然而，训练这些编码器不仅需要大量资源，且在许多情况下，可用数据不足以进行必要微调，这使得在受限环境和计算效率要求下学习LLMs颇具挑战性。因此，我们探索能够以最小努力将LLMs适配到ABSA的即插即用方法。

本文提出了一种整合可扩展组件的方法，这些组件能够纳入多种类型的句法知识，如成分句法、词语依存关系以及组合范畴语法（CCG）。具体来说，我们提出了一种记录句法信息的记忆模块，并将其集成到LLMs中以指导情感极性预测。重要的是，该编码器作为一个通用的、可分离的插件独立于LLMs进行训练。我们在基准数据集上进行实验，结果表明我们的方法优于强大的基线和先前方法，从而证明了其有效性。


> Aspect-based sentiment analysis (ABSA) generally requires a deep understanding of the contextual information, including the words associated with the aspect terms and their syntactic dependencies. Most existing studies employ advanced encoders (e.g., pre-trained models) to capture such context, especially large language models (LLMs). However, training these encoders is resource-intensive, and in many cases, the available data is insufficient for necessary fine-tuning. Therefore it is challenging for learning LLMs within such restricted environments and computation efficiency requirement. As a result, it motivates the exploration of plug-and-play methods that adapt LLMs to ABSA with minimal effort. In this paper, we propose an approach that integrates extendable components capable of incorporating various types of syntactic knowledge, such as constituent syntax, word dependencies, and combinatory categorial grammar (CCG). Specifically, we propose a memory module that records syntactic information and is incorporated into LLMs to instruct the prediction of sentiment polarities. Importantly, this encoder acts as a versatile, detachable plugin that is trained independently of the LLM. We conduct experiments on benchmark datasets, which show that our approach outperforms strong baselines and previous approaches, thus demonstrates its effectiveness.

[Arxiv](https://arxiv.org/abs/2506.12991)