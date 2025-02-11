# K-ON：在大型语言模型顶层实现知识叠加

发布时间：2025年02月10日

`LLM应用` `知识图谱`

> K-ON: Stacking Knowledge On the Head Layer of Large Language Model

# 摘要

> 近期，大型语言模型（LLMs）的突破显著提升了多种自然语言处理（NLP）任务的表现。通常，LLMs通过预测下一个词元进行训练，这与许多NLP任务高度契合。然而，在知识图谱（KG）场景中，实体是基本单位，识别一个实体至少需要几个词元。这导致了KG与自然语言之间的粒度不匹配。为了解决这一问题，我们提出了K-ON，它巧妙地将KG知识融入LLM，通过多头层预测下一步k步。K-ON不仅可以一步生成实体级别的结果，还支持基于实体的对比损失，这是KG表征学习中最强大的工具。实验结果表明，K-ON在性能上超越了现有的结合文本甚至其他模态的方法。

> Recent advancements in large language models (LLMs) have significantly improved various natural language processing (NLP) tasks. Typically, LLMs are trained to predict the next token, aligning well with many NLP tasks. However, in knowledge graph (KG) scenarios, entities are the fundamental units and identifying an entity requires at least several tokens. This leads to a granularity mismatch between KGs and natural languages. To address this issue, we propose K-ON, which integrates KG knowledge into the LLM by employing multiple head layers for next k-step prediction. K-ON can not only generate entity-level results in one step, but also enables contrastive loss against entities, which is the most powerful tool in KG representation learning. Experimental results show that K-ON outperforms state-of-the-art methods that incorporate text and even the other modalities.

[Arxiv](https://arxiv.org/abs/2502.06257)