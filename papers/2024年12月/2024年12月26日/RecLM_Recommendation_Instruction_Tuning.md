# RecLM: 推荐指令优化

发布时间：2024年12月26日

`LLM应用

**理由**：这篇论文主要讨论了如何将大型语言模型（LLM）与推荐系统结合，提出了一种模型无关的推荐指令调优框架，并开发了推荐语言模型（RecLM）。这属于将LLM应用于推荐系统的具体场景，因此分类为LLM应用。` `推荐系统` `人工智能`

> RecLM: Recommendation Instruction Tuning

# 摘要

> 现代推荐系统致力于通过用户历史交互深入解析其复杂偏好。尽管基于图神经网络（GNNs）的深度协同过滤在捕捉用户-物品关系上表现卓越，但在处理稀疏数据或零-shot场景时，其效能受限，主要归因于基于ID的嵌入函数的局限性。为应对这些挑战，我们提出了一种模型无关的推荐指令调优框架，巧妙地将大型语言模型与协同过滤融合。我们研发的推荐语言模型（RecLM）通过精心设计的强化学习奖励机制，强化了对用户偏好多样性的捕捉，促进了语言模型的自我进化。全面评估显示，我们的方法在多种情境下均展现出显著优势，且其即插即用的特性与顶尖推荐系统的无缝对接，实现了性能的显著跃升。

> Modern recommender systems aim to deeply understand users' complex preferences through their past interactions. While deep collaborative filtering approaches using Graph Neural Networks (GNNs) excel at capturing user-item relationships, their effectiveness is limited when handling sparse data or zero-shot scenarios, primarily due to constraints in ID-based embedding functions. To address these challenges, we propose a model-agnostic recommendation instruction-tuning paradigm that seamlessly integrates large language models with collaborative filtering. Our proposed Recommendation Language Model (RecLM) enhances the capture of user preference diversity through a carefully designed reinforcement learning reward function that facilitates self-augmentation of language models. Comprehensive evaluations demonstrate significant advantages of our approach across various settings, and its plug-and-play compatibility with state-of-the-art recommender systems results in notable performance enhancements.

[Arxiv](https://arxiv.org/abs/2412.19302)