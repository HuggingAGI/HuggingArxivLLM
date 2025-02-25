# MEMERAG：一个多语言端到端元评估基准，专为增强检索生成打造。

发布时间：2025年02月24日

`RAG` `多语言`

> MEMERAG: A Multilingual End-to-End Meta-Evaluation Benchmark for Retrieval Augmented Generation

# 摘要

> 检索增强生成（RAG）系统的自动评估依赖于细粒度的维度，如忠实度和相关性，这些维度由专业的标注人员进行判断。元评估基准支持开发与人工评价高度相关的自动评估器。然而，现有的基准主要关注英语或使用翻译数据，未能捕捉文化细微差别。采用本土化方法能更好地体现最终用户的体验。

在这项研究中，我们开发了一个多语言端到端元评估RAG基准（MEMERAG）。我们的基准建立在流行的MIRACL数据集之上，使用母语问题，并通过多种大型语言模型（LLMs）生成回答，随后由专家标注人员根据忠实度和相关性进行评估。我们描述了标注流程，并展示了其在标注者间达到了高度一致。接着，我们分析了回答生成LLMs在不同语言中的表现，依据人工评估结果。最后，我们将数据集应用于我们的主要用例，即基准测试多语言自动评估器（LLM作为裁判）。我们表明，我们的基准能够可靠地识别先进提示技术和LLMs带来的改进。我们发布了该基准，以支持社区开发多语言RAG系统的准确评估方法。

> Automatic evaluation of retrieval augmented generation (RAG) systems relies on fine-grained dimensions like faithfulness and relevance, as judged by expert human annotators. Meta-evaluation benchmarks support the development of automatic evaluators that correlate well with human judgement. However, existing benchmarks predominantly focus on English or use translated data, which fails to capture cultural nuances. A native approach provides a better representation of the end user experience.
  In this work, we develop a Multilingual End-to-end Meta-Evaluation RAG benchmark (MEMERAG). Our benchmark builds on the popular MIRACL dataset, using native-language questions and generating responses with diverse large language models (LLMs), which are then assessed by expert annotators for faithfulness and relevance. We describe our annotation process and show that it achieves high inter-annotator agreement. We then analyse the performance of the answer-generating LLMs across languages as per the human evaluators. Finally we apply the dataset to our main use-case which is to benchmark multilingual automatic evaluators (LLM-as-a-judge). We show that our benchmark can reliably identify improvements offered by advanced prompting techniques and LLMs. We release our benchmark to support the community developing accurate evaluation methods for multilingual RAG systems.

[Arxiv](https://arxiv.org/abs/2502.17163)