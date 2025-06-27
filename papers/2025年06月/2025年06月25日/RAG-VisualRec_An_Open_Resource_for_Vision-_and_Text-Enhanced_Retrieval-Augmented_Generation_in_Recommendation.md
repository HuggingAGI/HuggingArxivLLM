# RAG-VisualRec：一个专注于推荐领域的视觉与文本增强检索增强生成的开放资源。

发布时间：2025年06月25日

`LLM应用` `推荐系统`

> RAG-VisualRec: An Open Resource for Vision- and Text-Enhanced Retrieval-Augmented Generation in Recommendation

# 摘要

> 本文聚焦于电影领域多模态推荐系统的开发挑战，特别是如何克服有限元数据（如标题、类型）对稳健推荐生成的限制。我们提出了一种创新资源，通过结合大型语言模型（LLM）生成的剧情描述与预告片视觉嵌入，在统一框架下支持检索增强生成（RAG）和协同过滤技术。我们的方法以数据增强为核心，将稀疏元数据转化为丰富文本信号，并采用融合策略（如PCA、CCA）整合视觉信息。实验结果表明，基于CCA的融合策略显著提升了召回率，相较于单模态基线模型，而LLM驱动的重新排序步骤进一步优化了NDCG指标，尤其在文本数据有限的场景下表现突出。我们公开了这一框架，旨在促进针对冷启动、新颖性聚焦和领域特定场景的多模态推荐技术探索。所有代码、数据和详细文档均可在以下链接获取：https://github.com/RecSys-lab/RAG-VisualRec

> This paper addresses the challenge of developing multimodal recommender systems for the movie domain, where limited metadata (e.g., title, genre) often hinders the generation of robust recommendations. We introduce a resource that combines LLM-generated plot descriptions with trailer-derived visual embeddings in a unified pipeline supporting both Retrieval-Augmented Generation (RAG) and collaborative filtering. Central to our approach is a data augmentation step that transforms sparse metadata into richer textual signals, alongside fusion strategies (e.g., PCA, CCA) that integrate visual cues. Experimental evaluations demonstrate that CCA-based fusion significantly boosts recall compared to unimodal baselines, while an LLM-driven re-ranking step further improves NDCG, particularly in scenarios with limited textual data. By releasing this framework, we invite further exploration of multi-modal recommendation techniques tailored to cold-start, novelty-focused, and domain-specific settings. All code, data, and detailed documentation are publicly available at: https://github.com/RecSys-lab/RAG-VisualRec

[Arxiv](https://arxiv.org/abs/2506.20817)