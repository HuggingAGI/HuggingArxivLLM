# 向量数据库管理系统中的故障探索

发布时间：2025年06月03日

`其他` `推荐系统` `多模态搜索`

> Toward Understanding Bugs in Vector Database Management Systems

# 摘要

> 向量数据库管理系统（VDBMSs）在处理多源高维嵌入的语义相似度搜索中扮演着重要角色。尽管VDBMSs在推荐系统、检索增强生成（RAG）和多模态搜索等领域应用广泛，但其可靠性仍待深入研究。传统数据库的可靠性模型无法直接应用于VDBMSs，因为它们在数据表示、查询机制和系统架构上存在根本性差异。为解决这一问题，我们开展了首个针对VDBMS软件缺陷的大规模实证研究。通过对15个开源VDBMS的1,671个修复错误的拉取请求进行手动分析，我们基于错误症状、根本原因和修复策略构建了一个全面的分类体系。研究发现，VDBMSs存在五类典型错误症状，其中过半数表现为功能故障。我们还识别了31种常见故障模式，并揭示了向量搜索系统特有的故障类型。此外，总结了12种典型修复策略，其分布凸显了程序逻辑正确性的重要性。这些发现为提升VDBMS可靠性提供了重要参考，为未来构建更 robust 的系统指明了方向。

> Vector database management systems (VDBMSs) play a crucial role in facilitating semantic similarity searches over high-dimensional embeddings from diverse data sources. While VDBMSs are widely used in applications such as recommendation, retrieval-augmented generation (RAG), and multimodal search, their reliability remains underexplored. Traditional database reliability models cannot be directly applied to VDBMSs because of fundamental differences in data representation, query mechanisms, and system architecture. To address this gap, we present the first large-scale empirical study of software defects in VDBMSs. We manually analyzed 1,671 bug-fix pull requests from 15 widely used open-source VDBMSs and developed a comprehensive taxonomy of bugs based on symptoms, root causes, and developer fix strategies. Our study identifies five categories of bug symptoms, with more than half manifesting as functional failures. We further reveal 31 recurring fault patterns and highlight failure modes unique to vector search systems. In addition, we summarize 12 common fix strategies, whose distribution underscores the critical importance of correct program logic. These findings provide actionable insights into VDBMS reliability challenges and offer guidance for building more robust future systems.

[Arxiv](https://arxiv.org/abs/2506.02617)