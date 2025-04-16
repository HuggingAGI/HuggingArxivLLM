# 基于多模态超图增强的大语言模型推荐学习方法

发布时间：2025年04月13日

`LLM应用` `推荐系统` `图计算`

> Multi-Modal Hypergraph Enhanced LLM Learning for Recommendation

# 摘要

> 大型语言模型（LLM）的快速发展正在推动个性化推荐系统的革新。然而，现有基于LLM的方法大多未能充分挖掘推荐场景中的多视图图结构关联。针对这一问题，我们提出了一种名为HeLLM（超图增强的多模态推荐LLM学习方法）的创新框架，通过融合图级别上下文信号和序列级别行为模式，赋予LLMs捕捉复杂高阶语义关联的能力。在推荐系统预训练阶段，我们设计了用户超图来揭示用户间的共享兴趣偏好，并构建了物品超图来捕获物品间多模态相似性的关联。通过引入超图卷积和协同对比学习机制，我们增强了学习表示的区分度。在LLM微调阶段，我们将学习到的图结构嵌入直接注入LLM架构，并整合捕捉每位用户时序行为的序列特征。这一过程使超图能够利用图结构信息作为全局上下文，提升LLM感知复杂关系模式和整合多模态信息的能力，同时建模局部时序动态。大量实验结果表明，我们的方法在推荐任务中显著优于现有先进基线，证实了在LLMs中融合超图上下文与用户时序行为的优势。

> The burgeoning presence of Large Language Models (LLM) is propelling the development of personalized recommender systems. Most existing LLM-based methods fail to sufficiently explore the multi-view graph structure correlations inherent in recommendation scenarios. To this end, we propose a novel framework, Hypergraph Enhanced LLM Learning for multimodal Recommendation (HeLLM), designed to equip LLMs with the capability to capture intricate higher-order semantic correlations by fusing graph-level contextual signals with sequence-level behavioral patterns. In the recommender pre-training phase, we design a user hypergraph to uncover shared interest preferences among users and an item hypergraph to capture correlations within multimodal similarities among items. The hypergraph convolution and synergistic contrastive learning mechanism are introduced to enhance the distinguishability of learned representations. In the LLM fine-tuning phase, we inject the learned graph-structured embeddings directly into the LLM's architecture and integrate sequential features capturing each user's chronological behavior. This process enables hypergraphs to leverage graph-structured information as global context, enhancing the LLM's ability to perceive complex relational patterns and integrate multimodal information, while also modeling local temporal dynamics. Extensive experiments demonstrate the superiority of our proposed method over state-of-the-art baselines, confirming the advantages of fusing hypergraph-based context with sequential user behavior in LLMs for recommendation.

[Arxiv](https://arxiv.org/abs/2504.10541)