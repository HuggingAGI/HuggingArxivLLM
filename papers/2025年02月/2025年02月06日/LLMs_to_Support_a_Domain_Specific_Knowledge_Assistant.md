# LLMs 助力领域知识助手

发布时间：2025年02月06日

`RAG

理由：该论文主要讨论了基于国际财务报告准则（IFRS）的可持续发展报告领域的问答系统开发，重点介绍了两种架构：RAG管道和完全基于LLM的管道。RAG（Retrieval-Augmented Generation）是一种结合检索和生成的技术，用于提升问答系统的性能。论文中详细描述了RAG架构的开发、实验和性能评估，因此将其归类为RAG是合适的。` `财务报告` `可持续发展`

> LLMs to Support a Domain Specific Knowledge Assistant

# 摘要

> # 摘要
本研究提出了一种定制方法，用于开发基于国际财务报告准则（IFRS）的可持续发展报告领域知识助手。由于该领域缺乏公开的问答数据集，开发高质量聊天机器人以支持IFRS报告一直面临挑战。本项目的两大贡献如下：
  (1) 基于IFRS可持续发展标准的高质量合成问答（QA）数据集，利用大型语言模型（LLMs）通过创新的生成和评估流程创建。该数据集包含1,063个多样化的问答对，覆盖了可持续发展报告中的广泛用户查询。采用多种LLM技术，如思维链推理和少样本提示，创建数据集，并开发了定制评估框架，从忠实性、相关性和领域特异性等多个维度评估问答质量。该数据集在这些指标上的平均得分为8.16分（满分10分）。
  (2) 两种用于可持续发展报告领域的问答架构——RAG管道和完全基于LLM的管道。通过在QA数据集上进行实验、微调和训练，开发了这些架构。最终管道包括一个在领域特定数据上微调的LLM和一个行业分类组件，以提升复杂查询的处理能力。RAG架构在单一行业和跨行业多项选择题上的准确率分别为85.32%和72.15%，分别比基线方法高出4.67和19.21个百分点。基于LLM的管道在单一行业和跨行业多项选择题上的准确率分别为93.45%和80.30%，分别比基线方法高出12.80和27.36个百分点。

> This work presents a custom approach to developing a domain specific knowledge assistant for sustainability reporting using the International Financial Reporting Standards (IFRS). In this domain, there is no publicly available question-answer dataset, which has impeded the development of a high-quality chatbot to support companies with IFRS reporting. The two key contributions of this project therefore are:
  (1) A high-quality synthetic question-answer (QA) dataset based on IFRS sustainability standards, created using a novel generation and evaluation pipeline leveraging Large Language Models (LLMs). This comprises 1,063 diverse QA pairs that address a wide spectrum of potential user queries in sustainability reporting. Various LLM-based techniques are employed to create the dataset, including chain-of-thought reasoning and few-shot prompting. A custom evaluation framework is developed to assess question and answer quality across multiple dimensions, including faithfulness, relevance, and domain specificity. The dataset averages a score range of 8.16 out of 10 on these metrics.
  (2) Two architectures for question-answering in the sustainability reporting domain - a RAG pipeline and a fully LLM-based pipeline. The architectures are developed by experimenting, fine-tuning, and training on the QA dataset. The final pipelines feature an LLM fine-tuned on domain specific data and an industry classification component to improve the handling of complex queries. The RAG architecture achieves an accuracy of 85.32% on single-industry and 72.15% on cross-industry multiple-choice questions, outperforming the baseline approach by 4.67 and 19.21 percentage points, respectively. The LLM-based pipeline achieves an accuracy of 93.45% on single-industry and 80.30% on cross-industry multiple-choice questions, an improvement of 12.80 and 27.36 percentage points over the baseline, respectively.

[Arxiv](https://arxiv.org/abs/2502.04095)