# 检索增强生成：噪声环境中的上下文学习新理论与风险边界分析

发布时间：2025年06月03日

`RAG` `问答系统`

> Retrieval-Augmented Generation as Noisy In-Context Learning: A Unified Theory and Risk Bounds

# 摘要

> 近年来，检索增强生成（RAG）通过为大型语言模型（LLM）提供外部知识，在实践中取得了许多成功。然而，其理论方面仍然未被充分探索。本文中，我们提出了针对RAG在上下文线性回归中的首个有限样本泛化界限，并推导出精确的偏差方差权衡。我们的框架将检索到的文本视为与查询相关的噪声上下文示例，并将经典的上下文学习（ICL）和标准RAG视为极限情况。我们的分析表明，与ICL相比，RAG在泛化误差上存在一个内在的上限。此外，我们的框架能够通过引入均匀和非均匀的RAG噪声，同时建模从训练数据和外部语料库中检索的情况。与我们的理论一致，我们在常见的问答基准测试（如Natural Questions和TriviaQA）上进行了实验，实证展示了ICL和RAG的样本效率。

> Retrieval-augmented generation (RAG) has seen many empirical successes in recent years by aiding the LLM with external knowledge. However, its theoretical aspect has remained mostly unexplored. In this paper, we propose the first finite-sample generalization bound for RAG in in-context linear regression and derive an exact bias-variance tradeoff. Our framework views the retrieved texts as query-dependent noisy in-context examples and recovers the classical in-context learning (ICL) and standard RAG as the limit cases. Our analysis suggests that an intrinsic ceiling on generalization error exists on RAG as opposed to the ICL. Furthermore, our framework is able to model retrieval both from the training data and from external corpora by introducing uniform and non-uniform RAG noise. In line with our theory, we show the sample efficiency of ICL and RAG empirically with experiments on common QA benchmarks, such as Natural Questions and TriviaQA.

[Arxiv](https://arxiv.org/abs/2506.03100)