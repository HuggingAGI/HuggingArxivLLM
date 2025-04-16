# CCSK: 基于自知识认知对流的大型语言模型检索增强

发布时间：2025年04月07日

`RAG` `问答系统` `信息检索`

> CCSK:Cognitive Convection of Self-Knowledge Based Retrieval Augmentation for Large Language Models

# 摘要

> 大型语言模型（LLMs）在问答任务中的性能因检索增强生成（RAG）的引入而大幅提升，RAG通过整合外部知识增强了模型能力。然而，如何平衡LLMs自身的知识与外部信息检索（IR）仍是主要挑战。当前基于阈值的方法采用单一标准的静态机制，这可能导致在处理复杂查询时，IR决策与模型回答脱节。为解决这一问题，我们提出认知自知识对流（CCSK）。与传统方法不同，CCSK采用双子网络模块和响应质量模型实现动态联合决策。双子网络计算当前查询与历史查询的余弦相似度，而响应质量模型通过LightGBM评估LLMs的回答质量。最终，CCSK的决策基于两模块的输出，并结合多头注意力机制融合的文本特征。在真实数据集上的实验表明，CCSK显著提升了模型在信息检索中的效果。

> The performance of large language models (LLMs) in Q&A task increased substantially through Retrieval-Augmented Generation (RAG) which brings in external knowledge. However, the main difficulty lies in balancing the inherent self-knowledge of LLMs with external information retrieval (IR). The current threshold-based methods apply one-dimensional static mechanisms with single criterion. As a result, their IR decisions might be irrelevant to the LLMs' response under difficult queries. To alleviate this problem, we propose Cognitive Convection of Self-Knowledge (CCSK). Different from traditional methods that maintain single fixed IR activation criteria, CCSK implements a dynamic joint decision process via a Siamese Network module and a Response Quality Model. The Siamese Network calculates the cosine similarity between the current query and the historical queries. The Response Quality Model evaluates the responses of LLMs through LightGBM. The final decision of the CCSK is derived from the outputs of the two modules, as well as text features fused using a multi-head attention mechanism. Extensive experiments on real-world datasets show that CCSK significantly enhances the model's effectiveness in information retrieval.

[Arxiv](https://arxiv.org/abs/2504.10498)