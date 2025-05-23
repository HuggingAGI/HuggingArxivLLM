# BR-TaxQA-R：一个关于巴西个人所得税法的问答数据集，包含相关参考文献和判例法。

发布时间：2025年05月21日

`RAG` `问答系统`

> BR-TaxQA-R: A Dataset for Question Answering with References for Brazilian Personal Income Tax Law, including case law

# 摘要

> 本文推出全新数据集BR-TaxQA-R，专为巴西个人所得税法背景下的带参考问答任务而设计。该数据集整合了巴西税务局2024年官方问答文件中的715个问题，并加入巴西联邦税务局咨询委员会（CARF）的法律规定和行政裁决内容。我们采用OpenAI嵌入技术进行检索，结合GPT-4o-mini进行答案生成，构建了一个检索增强生成（RAG）流水线。通过对比多种文本分段策略，并基于RAGAS指标与ChatGPT和Perplexity.ai等商业工具进行对比测试。结果显示，我们的定制RAG流水线在“响应相关性”方面表现更优，表明其更精准理解用户查询，而商业模型在“事实正确性”和流畅性方面更具优势。这一结果反映了基于法律生成与语言流畅性之间的权衡关系。尤为重要的是，我们认为在税收等高风险领域，确保AI生成答案的法律合规性仍需依赖专业人工审核。BR-TaxQA-R数据集已开放获取，地址为：https://huggingface.co/datasets/unicamp-dl/BR-TaxQA-R。

> This paper presents BR-TaxQA-R, a novel dataset designed to support question answering with references in the context of Brazilian personal income tax law. The dataset contains 715 questions from the 2024 official Q\&A document published by Brazil's Internal Revenue Service, enriched with statutory norms and administrative rulings from the Conselho Administrativo de Recursos Fiscais (CARF). We implement a Retrieval-Augmented Generation (RAG) pipeline using OpenAI embeddings for searching and GPT-4o-mini for answer generation. We compare different text segmentation strategies and benchmark our system against commercial tools such as ChatGPT and Perplexity.ai using RAGAS-based metrics. Results show that our custom RAG pipeline outperforms commercial systems in Response Relevancy, indicating stronger alignment with user queries, while commercial models achieve higher scores in Factual Correctness and fluency. These findings highlight a trade-off between legally grounded generation and linguistic fluency. Crucially, we argue that human expert evaluation remains essential to ensure the legal validity of AI-generated answers in high-stakes domains such as taxation. BR-TaxQA-R is publicly available at https://huggingface.co/datasets/unicamp-dl/BR-TaxQA-R.

[Arxiv](https://arxiv.org/abs/2505.15916)