# 从意图发现到识别：主题建模与合成数据助力意图识别

发布时间：2025年05月16日

`LLM应用` `推荐系统` `客户意图识别`

> From Intent Discovery to Recognition with Topic Modeling and Synthetic Data

# 摘要

> 理解并识别AI系统中的客户意图至关重要，尤其在以简短表达和冷启动问题为特点的领域中，推荐系统需要在缺乏足够真实用户数据的情况下纳入新产品或服务。客户表达的特点是低频词共现和高度术语变异性，这对传统方法在明确用户需求和准备合成查询方面提出了巨大挑战。为解决此问题，我们提出了一种基于LLM的代理框架，用于主题建模和合成查询生成，以加速客户意图的发现和识别。首先，我们应用层次化主题建模和意图发现，将人工整理的36个通用用户意图扩展至278个细粒度意图，展示了LLMs在显著提升主题特异性和多样性方面的潜力。其次，为了支持新发现的意图并解决冷启动问题，我们生成合成用户查询数据，这不仅补充了真实表达，还减少了对人工标注的依赖，特别是在资源有限的情况下。主题模型实验表明，主题扩展后在连贯性和相关性上有显著提升，而合成数据实验则显示，基于类别的少样本提示显著提高了合成查询的质量和实用性，同时保持了多样性。我们还表明，LLM生成的意图描述和关键词在作为合成查询生成的上下文时，可以有效替代人工整理的版本。我们的研究强调了LLM代理在主题建模中的可扩展性和实用性，并突出了合成表达在增强数据集变异性以提高意图识别方面的战略价值。我们提出了一种全面而稳健的框架，用于动态领域中新型客户意图的在线发现与识别。

> Understanding and recognizing customer intents in AI systems is crucial, particularly in domains characterized by short utterances and the cold start problem, where recommender systems must include new products or services without sufficient real user data. Customer utterances are characterized by infrequent word co-occurences and high term variability, which poses significant challenges for traditional methods in specifying distinct user needs and preparing synthetic queries. To address this, we propose an agentic LLM framework for topic modeling and synthetic query generation, which accelerates the discovery and recognition of customer intents. We first apply hierarchical topic modeling and intent discovery to expand a human-curated taxonomy from 36 generic user intents to 278 granular intents, demonstrating the potential of LLMs to significantly enhance topic specificity and diversity. Next, to support newly discovered intents and address the cold start problem, we generate synthetic user query data, which augments real utterances and reduces dependency on human annotation, especially in low-resource settings. Topic model experiments show substantial improvements in coherence and relevance after topic expansion, while synthetic data experiments indicate that in-class few-shot prompting significantly improves the quality and utility of synthetic queries without compromising diversity. We also show that LLM-generated intent descriptions and keywords can effectively substitute for human-curated versions when used as context for synthetic query generation. Our research underscores the scalability and utility of LLM agents in topic modeling and highlights the strategic use of synthetic utterances to enhance dataset variability and coverage for intent recognition. We present a comprehensive and robust framework for online discovery and recognition of new customer intents in dynamic domains.

[Arxiv](https://arxiv.org/abs/2505.11176)