# Typed-RAG：类型感知的多方面分解，助力非事实性问题回答

发布时间：2025年03月20日

`RAG` `问答系统`

> Typed-RAG: Type-aware Multi-Aspect Decomposition for Non-Factoid Question Answering

# 摘要

> 非事实型问答（NFQA）因其开放性、多样化的意图及对多方面推理的需求，传统的事物型问答方法，包括检索增强生成（RAG），难以应对。与事实型问题不同，非事实型问题（NFQs）没有明确答案，需要跨多源信息综合推理。为此，我们提出了Typed-RAG，一种基于RAG范式的类型感知多方面分解框架，专为NFQA设计。Typed-RAG将NFQs分类为辩论、经验分享、比较等类型，并通过基于方面的分解优化检索与生成策略。通过将多方面的NFQs分解为单方面的子查询并整合结果，Typed-RAG能够生成更加丰富且上下文相关的回答。我们还推出了涵盖多种NFQ类型的基准数据集Wiki-NFQA。实验结果表明，Typed-RAG显著优于现有基线方法，凸显了类型感知分解在NFQA中实现有效检索与生成的重要性。我们的代码和数据集可在\href{https://github.com/TeamNLP/Typed-RAG}{https://github.com/TeamNLP/Typed-RAG}获取。

> Non-factoid question-answering (NFQA) poses a significant challenge due to its open-ended nature, diverse intents, and the need for multi-aspect reasoning, which renders conventional factoid QA approaches, including retrieval-augmented generation (RAG), inadequate. Unlike factoid questions, non-factoid questions (NFQs) lack definitive answers and require synthesizing information from multiple sources across various reasoning dimensions. To address these limitations, we introduce Typed-RAG, a type-aware multi-aspect decomposition framework within the RAG paradigm for NFQA. Typed-RAG classifies NFQs into distinct types -- such as debate, experience, and comparison -- and applies aspect-based decomposition to refine retrieval and generation strategies. By decomposing multi-aspect NFQs into single-aspect sub-queries and aggregating the results, Typed-RAG generates more informative and contextually relevant responses. To evaluate Typed-RAG, we introduce Wiki-NFQA, a benchmark dataset covering diverse NFQ types. Experimental results demonstrate that Typed-RAG outperforms baselines, thereby highlighting the importance of type-aware decomposition for effective retrieval and generation in NFQA. Our code and dataset are available at \href{https://github.com/TeamNLP/Typed-RAG}{https://github.com/TeamNLP/Typed-RAG}.

[Arxiv](https://arxiv.org/abs/2503.15879)