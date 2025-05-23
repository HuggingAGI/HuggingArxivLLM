# # R1-Searcher++：强化学习驱动大型语言模型动态知识获取

发布时间：2025年05月22日

`RAG` `人工智能` `知识管理`

> R1-Searcher++: Incentivizing the Dynamic Knowledge Acquisition of LLMs via Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）功能强大，但受限于静态知识，容易产生幻觉。检索增强生成（RAG）通过引入外部信息提供帮助，但现有方法往往面临成本高昂、泛化能力不足或忽视模型内部知识的挑战。本文提出R1-Searcher++，一个创新框架，旨在训练LLMs灵活运用内外部知识源。该框架采用两阶段训练策略：首先通过SFT冷启动阶段实现初步格式学习，随后借助强化学习（RL）进行动态知识获取。在RL阶段，我们采用结果监督机制鼓励探索，引入奖励机制促进内部知识的利用，并整合记忆机制持续吸收检索信息，从而不断丰富模型的内部知识。通过结合内部知识与外部搜索引擎，模型能够持续提升能力，实现高效的检索增强推理。实验结果表明，R1-Searcher++在性能上超越了现有的RAG和推理方法，并实现了高效的检索能力。我们的代码已开源，地址为https://github.com/RUCAIBox/R1-Searcher-plus。

> Large Language Models (LLMs) are powerful but prone to hallucinations due to static knowledge. Retrieval-Augmented Generation (RAG) helps by injecting external information, but current methods often are costly, generalize poorly, or ignore the internal knowledge of the model. In this paper, we introduce R1-Searcher++, a novel framework designed to train LLMs to adaptively leverage both internal and external knowledge sources. R1-Searcher++ employs a two-stage training strategy: an initial SFT Cold-start phase for preliminary format learning, followed by RL for Dynamic Knowledge Acquisition. The RL stage uses outcome-supervision to encourage exploration, incorporates a reward mechanism for internal knowledge utilization, and integrates a memorization mechanism to continuously assimilate retrieved information, thereby enriching the model's internal knowledge. By leveraging internal knowledge and external search engine, the model continuously improves its capabilities, enabling efficient retrieval-augmented reasoning. Our experiments demonstrate that R1-Searcher++ outperforms previous RAG and reasoning methods and achieves efficient retrieval. The code is available at https://github.com/RUCAIBox/R1-Searcher-plus.

[Arxiv](https://arxiv.org/abs/2505.17005)