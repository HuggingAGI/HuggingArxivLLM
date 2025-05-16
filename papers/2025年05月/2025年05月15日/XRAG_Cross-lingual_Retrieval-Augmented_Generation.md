# XRAG: 跨语言增强生成式检索

发布时间：2025年05月15日

`RAG` `跨语言处理` `信息检索`

> XRAG: Cross-lingual Retrieval-Augmented Generation

# 摘要

> 我们提出了一种名为XRAG的新基准测试，用于评估大型语言模型（LLMs）在跨语言检索增强生成（RAG）场景下的生成能力，特别是在用户语言与检索结果不匹配的情况下。XRAG基于近期新闻文章构建，确保所有问题都需要外部知识才能解答。它涵盖了单语和多语种检索的真实应用场景，并为每个检索到的文档提供了相关性标注。我们的新型数据集构建流程生成的问题需要复杂的推理能力，这一点从人类与LLMs性能之间的显著差距中可见一斑。因此，XRAG成为了一个研究LLMs推理能力的宝贵基准，即使不考虑额外的跨语言复杂性也是如此。在五个LLMs上的实验结果揭示了跨语言RAG中的两个全新挑战：1）在单语检索场景中，所有评估模型都难以确保响应语言的准确性；2）在多语种检索场景中，主要挑战在于跨语言推理检索到的信息，而非生成非英语文本。

> We propose XRAG, a novel benchmark designed to evaluate the generation abilities of LLMs in cross-lingual Retrieval-Augmented Generation (RAG) settings where the user language does not match the retrieval results. XRAG is constructed from recent news articles to ensure that its questions require external knowledge to be answered. It covers the real-world scenarios of monolingual and multilingual retrieval, and provides relevancy annotations for each retrieved document. Our novel dataset construction pipeline results in questions that require complex reasoning, as evidenced by the significant gap between human and LLM performance. Consequently, XRAG serves as a valuable benchmark for studying LLM reasoning abilities, even before considering the additional cross-lingual complexity. Experimental results on five LLMs uncover two previously unreported challenges in cross-lingual RAG: 1) in the monolingual retrieval setting, all evaluated models struggle with response language correctness; 2) in the multilingual retrieval setting, the main challenge lies in reasoning over retrieved information across languages rather than generation of non-English text.

[Arxiv](https://arxiv.org/abs/2505.10089)