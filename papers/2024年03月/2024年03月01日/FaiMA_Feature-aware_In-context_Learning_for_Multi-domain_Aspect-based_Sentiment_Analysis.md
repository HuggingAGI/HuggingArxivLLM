# FaiMA 是一项创新技术，专注于在多领域情境下进行特征感知的上下文学习，以提升基于方面的观点分析效果。

发布时间：2024年03月01日

`LLM应用`

> FaiMA: Feature-aware In-context Learning for Multi-domain Aspect-based Sentiment Analysis

# 摘要

> 多领域ABSA致力于捕获各领域的精细情感，而现有研究往往受限于方法局限性和数据稀少，集中于单一领域。然而，现实中情感往往会跨越多个领域。LLMs虽为ABSA带来了曙光，但因其内部结构不易调整，难以与诸如图模型和语言学等成熟技术紧密结合。为此，我们创新性地提出了“面向特征的多领域ABSA上下文学习”（简称FaiMA）框架。FaiMA的核心在于巧妙运用ICL作为感知特征的工具，助力在多领域ABSA任务中实现自适应学习。我们采用了一个经过精心设计的多头图注意力网络作为文本编码器，它能高效整合语言、领域及情感特征。借助对比学习策略，我们聚焦这些多元特征优化句子表征。同时，我们构建了一个高效的索引系统，使得FaiMA能够在任意输入下跨多个维度精准召回高度相关的示例。为了验证FaiMA的效果，我们创建了首个多领域ABSA基准数据集，并进行了广泛实验。结果显示，相较于对照组，FaiMA在多个领域均有显著性能提升，平均F1值增长了2.07%。相关源代码和数据集可在https://github.com/SupritYoung/FaiMA上匿名获取。

> Multi-domain aspect-based sentiment analysis (ABSA) seeks to capture fine-grained sentiment across diverse domains. While existing research narrowly focuses on single-domain applications constrained by methodological limitations and data scarcity, the reality is that sentiment naturally traverses multiple domains. Although large language models (LLMs) offer a promising solution for ABSA, it is difficult to integrate effectively with established techniques, including graph-based models and linguistics, because modifying their internal architecture is not easy. To alleviate this problem, we propose a novel framework, Feature-aware In-context Learning for Multi-domain ABSA (FaiMA). The core insight of FaiMA is to utilize in-context learning (ICL) as a feature-aware mechanism that facilitates adaptive learning in multi-domain ABSA tasks. Specifically, we employ a multi-head graph attention network as a text encoder optimized by heuristic rules for linguistic, domain, and sentiment features. Through contrastive learning, we optimize sentence representations by focusing on these diverse features. Additionally, we construct an efficient indexing mechanism, allowing FaiMA to stably retrieve highly relevant examples across multiple dimensions for any given input. To evaluate the efficacy of FaiMA, we build the first multi-domain ABSA benchmark dataset. Extensive experimental results demonstrate that FaiMA achieves significant performance improvements in multiple domains compared to baselines, increasing F1 by 2.07% on average. Source code and data sets are anonymously available at https://github.com/SupritYoung/FaiMA.

[Arxiv](https://arxiv.org/abs/2403.01063)