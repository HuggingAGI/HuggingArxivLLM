# # 超越函数级别的代码摘要

发布时间：2025年02月23日

`LLM应用` `软件工程` `代码总结`

> Code Summarization Beyond Function Level

# 摘要

> 代码总结是自然语言处理与软件工程中的重要任务，旨在为源代码生成简洁的描述。近期研究提升了摘要质量，改善了代码的可读性和维护性。然而，现有研究尚未将代码库或类的上下文纳入函数级代码总结的考量。本研究探索了代码总结模型在超越函数级的适用性，深入分析了类和代码库上下文对摘要质量的影响。

研究内容包括：修订类级和代码库级的评估基准，评估基线模型，以及通过带上下文学习的大语言模型评估，以验证额外上下文对摘要质量的提升。研究发现，经过微调的CodeT5+基础模型在代码总结中表现优异，而结合少量样本学习和从RAG检索的代码片段显著提升了大语言模型的性能。Deepseek Coder 1.3B和Starcoder2 15B模型在类级和代码库级的BLEURT、METEOR和BLEU-4等指标上均取得了显著提升。

代码库级总结展现出巨大潜力，但需要大量计算资源，并且从结构化上下文中获益匪浅。此外，我们在评估中采用了最新的SIDE代码总结指标。本研究为优化提示工程、少量样本学习和RAG策略提供了重要参考，弥补了代码总结在不同层级上的基准空白。最后，我们将在GitHub仓库（https://github.com/kilimanj4r0/code-summarization-beyond-function-level）中公开研究详情、代码、数据集和评估结果。

> Code summarization is a critical task in natural language processing and software engineering, which aims to generate concise descriptions of source code. Recent advancements have improved the quality of these summaries, enhancing code readability and maintainability. However, the content of a repository or a class has not been considered in function code summarization. This study investigated the effectiveness of code summarization models beyond the function level, exploring the impact of class and repository contexts on the summary quality. The study involved revising benchmarks for evaluating models at class and repository levels, assessing baseline models, and evaluating LLMs with in-context learning to determine the enhancement of summary quality with additional context. The findings revealed that the fine-tuned state-of-the-art CodeT5+ base model excelled in code summarization, while incorporating few-shot learning and retrieved code chunks from RAG significantly enhanced the performance of LLMs in this task. Notably, the Deepseek Coder 1.3B and Starcoder2 15B models demonstrated substantial improvements in metrics such as BLEURT, METEOR, and BLEU-4 at both class and repository levels. Repository-level summarization exhibited promising potential but necessitates significant computational resources and gains from the inclusion of structured context. Lastly, we employed the recent SIDE code summarization metric in our evaluation. This study contributes to refining strategies for prompt engineering, few-shot learning, and RAG, addressing gaps in benchmarks for code summarization at various levels. Finally, we publish all study details, code, datasets, and results of evaluation in the GitHub repository available at https://github.com/kilimanj4r0/code-summarization-beyond-function-level.

[Arxiv](https://arxiv.org/abs/2502.16704)