# 门控机制在 LLM 中的记忆与知识注入

发布时间：2025年04月29日

`LLM理论` `人工智能` `机器学习`

> Memorization and Knowledge Injection in Gated LLMs

# 摘要

> 大型语言模型（LLMs）在序列添加新记忆和整合新知识方面仍存在挑战，这与人类能够终身学习新知识的能力形成对比。现有方法通常通过扩大上下文窗口或引入外部记忆缓冲区（如检索增强生成）来添加记忆，而知识注入研究较少涉及日常事件场景。我们提出了一种持续学习框架——门控LLM中的记忆嵌入（MEGa），该框架通过门控机制将事件记忆直接注入LLMs权重中。每个记忆存储在专门的门控低秩权重集中，推理时通过匹配查询嵌入与存储记忆嵌入激活相关权重，从而实现完整记忆的回忆与相关问题的回答。在虚构角色和维基百科事件两个数据集上，MEGa在缓解灾难性遗忘方面优于基线方法。我们的模型灵感来源于人类大脑的互补记忆系统。

> Large Language Models (LLMs) currently struggle to sequentially add new memories and integrate new knowledge. These limitations contrast with the human ability to continuously learn from new experiences and acquire knowledge throughout life. Most existing approaches add memories either through large context windows or external memory buffers (e.g., Retrieval-Augmented Generation), and studies on knowledge injection rarely test scenarios resembling everyday life events. In this work, we introduce a continual learning framework, Memory Embedded in Gated LLMs (MEGa), which injects event memories directly into the weights of LLMs. Each memory is stored in a dedicated set of gated low-rank weights. During inference, a gating mechanism activates relevant memory weights by matching query embeddings to stored memory embeddings. This enables the model to both recall entire memories and answer related questions. On two datasets - fictional characters and Wikipedia events - MEGa outperforms baseline approaches in mitigating catastrophic forgetting. Our model draws inspiration from the complementary memory system of the human brain.

[Arxiv](https://arxiv.org/abs/2504.21239)