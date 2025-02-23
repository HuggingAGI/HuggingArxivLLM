# 用于检索增强生成的认知对齐文档选择

发布时间：2025年02月17日

`RAG` `信息检索`

> Cognitive-Aligned Document Selection for Retrieval-augmented Generation

# 摘要

> 大型语言模型（LLMs）固有的幻觉现象源于其生成文本的精度无法仅凭参数化知识保证。尽管检索增强生成（RAG）系统通过整合外部文档提升了生成模型的准确性和可靠性，但在实际应用中，检索到的文档往往无法充分支持模型的回答。为解决这一问题，我们提出了GGatrieval（细粒度 grounded 对齐检索，用于可验证生成），该方法利用LLM动态更新查询并筛选高质量、可靠的检索文档。

具体来说，我们将用户查询解析为其句法成分，并与检索到的文档进行细粒度的 grounded 对齐。对于无法单独对齐的查询成分，我们提出了一种动态语义补偿机制，通过迭代优化和重写查询，同时持续更新检索结果。这一迭代过程持续进行，直到检索到的文档足以支持查询的回答。

我们的方法引入了一种新颖的检索文档筛选标准，紧密模仿了人类获取目标信息的策略。这确保了检索到的内容能够有效支持和验证生成的输出。在ALCE基准测试中，我们的方法显著超越了各种基线，达到了最先进的性能水平。

> Large language models (LLMs) inherently display hallucinations since the precision of generated texts cannot be guaranteed purely by the parametric knowledge they include. Although retrieval-augmented generation (RAG) systems enhance the accuracy and reliability of generative models by incorporating external documents, these retrieved documents often fail to adequately support the model's responses in practical applications. To address this issue, we propose GGatrieval (Fine-\textbf{G}rained \textbf{G}rounded \textbf{A}lignment Re\textbf{trieval} for verifiable generation), which leverages an LLM to dynamically update queries and filter high-quality, reliable retrieval documents. Specifically, we parse the user query into its syntactic components and perform fine-grained grounded alignment with the retrieved documents. For query components that cannot be individually aligned, we propose a dynamic semantic compensation mechanism that iteratively refines and rewrites the query while continuously updating the retrieval results. This iterative process continues until the retrieved documents sufficiently support the query's response. Our approach introduces a novel criterion for filtering retrieved documents, closely emulating human strategies for acquiring targeted information. This ensures that the retrieved content effectively supports and verifies the generated outputs. On the ALCE benchmark, our method significantly surpasses a wide range of baselines, achieving state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2502.11770)