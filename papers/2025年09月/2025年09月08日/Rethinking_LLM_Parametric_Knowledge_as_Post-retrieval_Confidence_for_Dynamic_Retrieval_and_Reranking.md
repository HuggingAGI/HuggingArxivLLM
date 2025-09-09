# 重新思考LLM参数化知识：动态检索与重排序的检索后置信度

发布时间：2025年09月08日

`RAG` `基础理论`

> Rethinking LLM Parametric Knowledge as Post-retrieval Confidence for Dynamic Retrieval and Reranking

# 摘要

> 大型语言模型（LLMs）在遇到超出自身知识范围的问题时，常常会生成不准确的回答（即幻觉现象）。检索增强生成（RAG）通过引入外部知识解决了这一问题，但仍面临一个关键挑战：如何判断检索到的上下文是否能有效提升模型回答特定查询的能力。这一挑战凸显了知识边界感知的重要性，然而当前方法依赖离散标签或有限信号，忽略了LLMs连续内部隐藏状态中蕴含的丰富信息，因此无法充分应对。为此，我们提出了一种全新的检索后知识过滤方法。首先，基于LLMs的内部隐藏状态构建置信度检测模型，用于量化检索上下文对模型置信度的增强效果；接着，利用该模型构建偏好数据集（NQ_Rerank），以微调重排序器，使其在重排序时能优先选取下游LLM偏好的上下文。此外，我们还引入基于置信度的动态检索（CBDR），根据LLM对原始问题的初始置信度自适应触发检索，从而减少知识冲突并提升效率。实验结果显示，该方法不仅显著提高了上下文筛选和端到端RAG的准确性，还在保持精度竞争力的同时大幅降低了检索成本。

> Large Language Models (LLMs) often generate inaccurate responses (hallucinations) when faced with questions beyond their knowledge scope. Retrieval-Augmented Generation (RAG) addresses this by leveraging external knowledge, but a critical challenge remains: determining whether retrieved contexts effectively enhance the model`s ability to answer specific queries. This challenge underscores the importance of knowledge boundary awareness, which current methods-relying on discrete labels or limited signals-fail to address adequately, as they overlook the rich information in LLMs` continuous internal hidden states. To tackle this, we propose a novel post-retrieval knowledge filtering approach. First, we construct a confidence detection model based on LLMs` internal hidden states to quantify how retrieved contexts enhance the model`s confidence. Using this model, we build a preference dataset (NQ_Rerank) to fine-tune a reranker, enabling it to prioritize contexts preferred by the downstream LLM during reranking. Additionally, we introduce Confidence-Based Dynamic Retrieval (CBDR), which adaptively triggers retrieval based on the LLM`s initial confidence in the original question, reducing knowledge conflicts and improving efficiency. Experimental results demonstrate significant improvements in accuracy for context screening and end-to-end RAG performance, along with a notable reduction in retrieval costs while maintaining competitive accuracy.

[Arxiv](https://arxiv.org/abs/2509.06472)