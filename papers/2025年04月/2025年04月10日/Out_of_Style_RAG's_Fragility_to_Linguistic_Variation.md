# 过时的风格：RAG在语言变体中的脆弱性分析

发布时间：2025年04月10日

`RAG` `问答系统`

> Out of Style: RAG's Fragility to Linguistic Variation

# 摘要

> 尽管检索增强生成（RAG）系统在各种NLP基准测试中表现优异，但它们在处理现实世界用户与LLM交互查询时的鲁棒性研究仍显不足。这一空白对实际部署至关重要，因为用户查询往往表现出更大的语言变体，并可能触发RAG组件之间的级联错误。本研究系统性地分析了四个语言维度（正式性、可读性、礼貌性和语法正确性）的变化如何影响RAG性能。我们评估了两个检索模型和九种LLM，参数范围从30亿到720亿，涵盖四个信息检索问答（QA）数据集。结果显示，语言重构显著影响检索和生成阶段，非正式查询的Recall@5得分相对下降高达40.41%，而包含语法错误的查询在答案匹配得分上则下降了38.86%。值得注意的是，与仅基于LLM的生成相比，RAG系统对这些变化更为敏感，突显了它们在面对语言变化时易受错误传播影响的脆弱性。这些发现强调了开发改进的鲁棒性技术的必要性，以增强在多样化用户互动中的可靠性。

> Despite the impressive performance of Retrieval-augmented Generation (RAG) systems across various NLP benchmarks, their robustness in handling real-world user-LLM interaction queries remains largely underexplored. This presents a critical gap for practical deployment, where user queries exhibit greater linguistic variations and can trigger cascading errors across interdependent RAG components. In this work, we systematically analyze how varying four linguistic dimensions (formality, readability, politeness, and grammatical correctness) impact RAG performance. We evaluate two retrieval models and nine LLMs, ranging from 3 to 72 billion parameters, across four information-seeking Question Answering (QA) datasets. Our results reveal that linguistic reformulations significantly impact both retrieval and generation stages, leading to a relative performance drop of up to 40.41% in Recall@5 scores for less formal queries and 38.86% in answer match scores for queries containing grammatical errors. Notably, RAG systems exhibit greater sensitivity to such variations compared to LLM-only generations, highlighting their vulnerability to error propagation due to linguistic shifts. These findings highlight the need for improved robustness techniques to enhance reliability in diverse user interactions.

[Arxiv](https://arxiv.org/abs/2504.08231)