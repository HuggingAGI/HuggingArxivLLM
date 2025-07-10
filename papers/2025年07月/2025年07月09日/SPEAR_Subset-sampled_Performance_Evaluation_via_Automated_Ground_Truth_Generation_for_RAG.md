# SPEAR: 基于自动化生成真实标签的 RAG 子集采样性能评估方法

发布时间：2025年07月09日

`RAG`

> SPEAR: Subset-sampled Performance Evaluation via Automated Ground Truth Generation for RAG

# 摘要

> 检索增强生成（RAG）是提升大型语言模型（LLMs）性能的核心方法，其中检索器的有效性在很大程度上决定了RAG系统整体的响应质量。检索器包含大量超参数，这些超参数对性能结果产生重大影响，并且对特定应用表现出敏感性。然而，超参数优化需要付出高昂的计算成本。现有的评估方法要么成本过高，要么与特定领域场景脱节。本文提出了一种名为SEARA（Subset sampling Evaluation for Automatic Retriever Assessment，基于子集采样的自动检索器评估方法），通过子集采样技术解决评估数据的挑战，并通过最小的检索事实提取和全面的检索指标实现稳健的自动检索器评估。基于真实用户查询，该方法能够在低成本下实现完全自动化的检索器评估，从而为特定业务场景获得最优的检索器。我们在rednote的经典RAG应用中验证了我们的方法，包括基于知识的问答系统和基于检索的旅游助手，成功获得了针对具体场景的最优检索器。

> Retrieval-Augmented Generation (RAG) is a core approach for enhancing Large Language Models (LLMs), where the effectiveness of the retriever largely determines the overall response quality of RAG systems. Retrievers encompass a multitude of hyperparameters that significantly impact performance outcomes and demonstrate sensitivity to specific applications. Nevertheless, hyperparameter optimization entails prohibitively high computational expenses. Existing evaluation methods suffer from either prohibitive costs or disconnection from domain-specific scenarios. This paper proposes SEARA (Subset sampling Evaluation for Automatic Retriever Assessment), which addresses evaluation data challenges through subset sampling techniques and achieves robust automated retriever evaluation by minimal retrieval facts extraction and comprehensive retrieval metrics. Based on real user queries, this method enables fully automated retriever evaluation at low cost, thereby obtaining optimal retriever for specific business scenarios. We validate our method across classic RAG applications in rednote, including knowledge-based Q&A system and retrieval-based travel assistant, successfully obtaining scenario-specific optimal retrievers.

[Arxiv](https://arxiv.org/abs/2507.06554)