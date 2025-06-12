# # 大型语言模型中的查询级别不确定性分析

发布时间：2025年06月11日

`LLM理论` `问答系统`

> Query-Level Uncertainty in Large Language Models

# 摘要

> 大型语言模型需要具备认知自身知识边界的能力，即区分已知与未知查询的机制。这种能力使模型能够进行自适应推理，例如调用RAG机制、进行深度思考或采用弃用机制，从而推动高效可靠的人工智能发展。本研究提出了一种基于查询级别不确定性的知识边界检测方法，旨在判断模型能否在不生成任何标记的情况下处理给定查询。为此，我们引入了一种无需训练的新方法——\emph{内部置信度}，该方法通过跨层和跨标记的自我评估实现。实验结果表明，在事实问答和数学推理任务中，我们的内部置信度优于多个基线方法。此外，我们的方法还可用于高效RAG和模型级联，在保持性能的同时降低推理成本。

> It is important for Large Language Models to be aware of the boundary of their knowledge, the mechanism of identifying known and unknown queries. This type of awareness can help models perform adaptive inference, such as invoking RAG, engaging in slow and deep thinking, or adopting the abstention mechanism, which is beneficial to the development of efficient and trustworthy AI. In this work, we propose a method to detect knowledge boundaries via Query-Level Uncertainty, which aims to determine if the model is able to address a given query without generating any tokens. To this end, we introduce a novel and training-free method called \emph{Internal Confidence}, which leverages self-evaluations across layers and tokens. Empirical results on both factual QA and mathematical reasoning tasks demonstrate that our internal confidence can outperform several baselines. Furthermore, we showcase that our proposed method can be used for efficient RAG and model cascading, which is able to reduce inference costs while maintaining performance.

[Arxiv](https://arxiv.org/abs/2506.09669)