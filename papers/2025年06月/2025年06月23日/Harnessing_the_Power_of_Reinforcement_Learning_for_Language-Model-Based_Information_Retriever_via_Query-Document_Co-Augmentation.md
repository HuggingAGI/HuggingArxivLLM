# 强化学习助力语言模型驱动的信息检索：查询-文档协同增强策略

发布时间：2025年06月23日

`LLM应用` `信息检索`

> Harnessing the Power of Reinforcement Learning for Language-Model-Based Information Retriever via Query-Document Co-Augmentation

# 摘要

> 近期研究提出通过查询改写的方式利用大语言模型（LLMs）作为信息检索器。然而，对于具有挑战性的语料库，我们主张仅增强查询不足以实现稳健的语义匹配。LLM还应该通过直接处理和增强文档本身来充分理解语料库。为此，我们提出了一种能够增强用户查询和语料库文档的LLM基检索器，其策略通过强化学习（RL）得到了充分探索，且引入了最小的人为归纳偏见。值得注意的是，我们发现仅允许LLM修改文档几乎没有任何效果，除非将其与我们精心设计的双向RL框架相结合，该框架使LLM能够同时学习和协作完成查询和文档增强策略。实现这一框架的关键技术挑战在于训练过程中同时更新两个策略，其中两个方向的奖励相互依赖，导致难以处理的纠缠奖励。我们的方法通过引入一种奖励采样策略和一种专门设计的RL算法，使利用这些采样奖励进行有效训练成为可能。实验结果表明，我们的方法在稀疏和密集设置下显著提升了LLM基检索性能，特别是在困难检索领域，并实现了强大的跨基准泛化能力。我们的代码已发布在https://github.com/liujm2001/CoAugRetriever。

> Recent studies have proposed leveraging Large Language Models (LLMs) as information retrievers through query rewriting. However, for challenging corpora, we argue that enhancing queries alone is insufficient for robust semantic matching; the LLM should also have sufficient understanding of the corpus by directly handling and augmenting the documents themselves. To this end, we present an LLM-based retriever empowered to augment both user queries and corpus documents, with its policy fully explored via reinforcement learning (RL) and minimal human inductive bias. Notably, we find that simply allowing the LLM to modify documents yields little benefit unless paired with our carefully designed bidirectional RL framework, which enables the LLM to simultaneously learn and collaborate on both query and document augmentation policies. A key technical challenge in realizing such a framework lies in jointly updating both policies during training, where the rewards for the two directions depend on each other, making their entangled reward intractable. Our approach addresses this by introducing a reward sampling strategy and a specifically designed RL algorithm that enables effective training with these sampled rewards. Experimental results demonstrate that our approach significantly enhances LLM-based retrieval performance in both sparse and dense settings, particularly in difficult retrieval domains, and achieves strong cross-benchmark generalization. Our code is released at https://github.com/liujm2001/CoAugRetriever.

[Arxiv](https://arxiv.org/abs/2506.18670)