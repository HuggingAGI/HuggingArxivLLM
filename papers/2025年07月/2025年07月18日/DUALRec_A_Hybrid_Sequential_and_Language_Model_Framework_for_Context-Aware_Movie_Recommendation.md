# DUALRec：融合序列模型与语言模型的混合框架，专为情境感知式电影推荐而设计

发布时间：2025年07月18日

`LLM应用` `推荐系统` `电子商务`

> DUALRec: A Hybrid Sequential and Language Model Framework for Context-Aware Movie Recommendation

# 摘要

> 现代推荐系统面临着建模和预测动态且上下文丰富的用户偏好的日益严峻的挑战。传统的协同过滤和基于内容的方法往往难以捕捉时间模式和不断演变的用户意图。虽然大型语言模型（LLMs）因其强大的语义理解和推理能力而受到关注，但它们并非专门设计来建模随时间演变的用户偏好和意图。另一方面，LSTM（长短期记忆）模型擅长捕捉用户行为的动态变化和随时间演变的偏好，但缺乏全面推荐所需的丰富语义理解能力。为了解决这一问题，我们提出了DUALRec（动态用户感知语言推荐系统），这是一种结合了LSTM网络的时间建模能力和微调后大型语言模型语义推理能力的新型推荐系统。LSTM组件通过用户的观看历史捕捉其偏好的演变，而微调后的LLM变体则利用这些时间洞察力生成用户可能喜欢的推荐内容。在MovieLens-1M数据集上的实验表明，DUALRec模型在Hit Rate（HR@k）、Normalized Discounted Cumulative Gain（NDCG@k）和类型相似性等综合评估指标上优于多种基线模型。这项研究提出了一种新颖的架构，成功将时间序列建模与语义推理相结合，为开发更智能和上下文感知的推荐系统指明了方向。

> The modern recommender systems are facing an increasing challenge of modelling and predicting the dynamic and context-rich user preferences. Traditional collaborative filtering and content-based methods often struggle to capture the temporal patternings and evolving user intentions. While Large Language Models (LLMs) have gained gradual attention in recent years, by their strong semantic understanding and reasoning abilities, they are not inherently designed to model chronologically evolving user preference and intentions. On the other hand, for sequential models like LSTM (Long-Short-Term-Memory) which is good at capturing the temporal dynamics of user behaviour and evolving user preference over time, but still lacks a rich semantic understanding for comprehensive recommendation generation. In this study, we propose DUALRec (Dynamic User-Aware Language-based Recommender), a novel recommender that leverages the complementary strength of both models, which combines the temporal modelling abilities of LSTM networks with semantic reasoning power of the fine-tuned Large Language Models. The LSTM component will capture users evolving preference through their viewing history, while the fine-tuned LLM variants will leverage these temporal user insights to generate next movies that users might enjoy. Experimental results on MovieLens-1M dataset shows that the DUALRec model outperforms a wide range of baseline models, with comprehensive evaluation matrices of Hit Rate (HR@k), Normalized Discounted Cumulative Gain (NDCG@k), and genre similarity metrics. This research proposes a novel architecture that bridges the gap between temporal sequence modeling and semantic reasoning, and offers a promising direction for developing more intelligent and context-aware recommenders.

[Arxiv](https://arxiv.org/abs/2507.13957)