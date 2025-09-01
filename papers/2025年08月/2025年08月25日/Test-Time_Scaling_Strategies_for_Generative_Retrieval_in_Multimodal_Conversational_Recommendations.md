# 多模态对话推荐中生成式检索的测试时扩展策略

发布时间：2025年08月25日

`LLM应用` `零售与电商`

> Test-Time Scaling Strategies for Generative Retrieval in Multimodal Conversational Recommendations

# 摘要

> 电子商务的飞速发展凸显了传统产品检索系统在应对复杂多轮用户交互时的不足。多模态生成式检索的最新突破——特别是采用多模态大型语言模型（MLLMs）作为检索器的方案——已展现出良好前景。但多数现有方法专为单轮场景定制，直接应用于多轮对话时，难以捕捉用户意图的动态变化和对话的迭代特性。与此同时，测试时扩展作为一种通过迭代推理优化提升大型语言模型（LLM）性能的有效范式逐渐兴起。但其效果往往依赖两个前提：（1）问题空间定义清晰（如数学推理），（2）模型具备自我修正能力——而这些条件在对话式产品搜索中鲜少满足。在此场景下，用户查询常模糊多变，仅靠MLLMs难以将检索结果准确关联到固定产品库。针对这些挑战，我们提出一种将测试时扩展融入对话式多模态产品检索的全新框架。该方案以生成式检索器为基础，新增测试时重排序（TTR）机制，不仅提升了检索精度，还能在整个对话过程中更好地匹配用户意图的动态变化。多项基准测试表明，该方法效果稳定提升，MRR平均提高14.5个百分点，nDCG@1平均提高10.6个百分点。

> The rapid evolution of e-commerce has exposed the limitations of traditional product retrieval systems in managing complex, multi-turn user interactions. Recent advances in multimodal generative retrieval -- particularly those leveraging multimodal large language models (MLLMs) as retrievers -- have shown promise. However, most existing methods are tailored to single-turn scenarios and struggle to model the evolving intent and iterative nature of multi-turn dialogues when applied naively. Concurrently, test-time scaling has emerged as a powerful paradigm for improving large language model (LLM) performance through iterative inference-time refinement. Yet, its effectiveness typically relies on two conditions: (1) a well-defined problem space (e.g., mathematical reasoning), and (2) the model's ability to self-correct -- conditions that are rarely met in conversational product search. In this setting, user queries are often ambiguous and evolving, and MLLMs alone have difficulty grounding responses in a fixed product corpus. Motivated by these challenges, we propose a novel framework that introduces test-time scaling into conversational multimodal product retrieval. Our approach builds on a generative retriever, further augmented with a test-time reranking (TTR) mechanism that improves retrieval accuracy and better aligns results with evolving user intent throughout the dialogue. Experiments across multiple benchmarks show consistent improvements, with average gains of 14.5 points in MRR and 10.6 points in nDCG@1.

[Arxiv](https://arxiv.org/abs/2508.18132)