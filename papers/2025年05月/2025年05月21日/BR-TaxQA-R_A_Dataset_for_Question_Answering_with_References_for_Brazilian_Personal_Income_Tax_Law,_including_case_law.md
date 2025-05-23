# BR-TaxQA-R：一个关于巴西个人所得税法的问答数据集，并包含相关判例法

发布时间：2025年05月21日

`RAG` `问答系统`

> BR-TaxQA-R: A Dataset for Question Answering with References for Brazilian Personal Income Tax Law, including case law

# 摘要

> 本文介绍了一个新颖的数据集 BR-TaxQA-R，旨在支持巴西个人所得税法背景下的问答任务，提供参考依据。该数据集包含了巴西税务局发布的 2024 年官方问答文件中的 715 个问题，并补充了来自 Conselho Administrativo de Recursos Fiscais (CARF) 的法定规范和行政裁决。我们使用 OpenAI 嵌入进行搜索，并采用 GPT-4o-mini 进行答案生成，构建了一个检索增强生成（RAG）管道。我们比较了不同的文本分割策略，并使用基于 RAGAS 的指标，将我们的系统与 ChatGPT 和 Perplexity.ai 等商业工具进行了基准测试。结果显示，我们的定制 RAG 管道在响应相关性方面优于商业系统，表明与用户查询的更强对齐，而商业模型在事实正确性和流畅性方面得分更高。这些发现突显了基于法律的生成与语言流畅性之间的权衡。至关重要的是，我们认为在税收等高风险领域，确保 AI 生成答案的法律有效性仍需人类专家评估。BR-TaxQA-R 数据集可公开获取，地址为 https://huggingface.co/datasets/unicamp-dl/BR-TaxQA-R。


> This paper presents BR-TaxQA-R, a novel dataset designed to support question answering with references in the context of Brazilian personal income tax law. The dataset contains 715 questions from the 2024 official Q\&A document published by Brazil's Internal Revenue Service, enriched with statutory norms and administrative rulings from the Conselho Administrativo de Recursos Fiscais (CARF). We implement a Retrieval-Augmented Generation (RAG) pipeline using OpenAI embeddings for searching and GPT-4o-mini for answer generation. We compare different text segmentation strategies and benchmark our system against commercial tools such as ChatGPT and Perplexity.ai using RAGAS-based metrics. Results show that our custom RAG pipeline outperforms commercial systems in Response Relevancy, indicating stronger alignment with user queries, while commercial models achieve higher scores in Factual Correctness and fluency. These findings highlight a trade-off between legally grounded generation and linguistic fluency. Crucially, we argue that human expert evaluation remains essential to ensure the legal validity of AI-generated answers in high-stakes domains such as taxation. BR-TaxQA-R is publicly available at https://huggingface.co/datasets/unicamp-dl/BR-TaxQA-R.

[Arxiv](https://arxiv.org/abs/2505.15916)