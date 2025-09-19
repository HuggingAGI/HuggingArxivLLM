# DeKeyNLU：通过任务分解与关键词提取提升自然语言转SQL生成

发布时间：2025年09月17日

`RAG` `基础理论`

> DeKeyNLU: Enhancing Natural Language to SQL Generation through Task Decomposition and Keyword Extraction

# 摘要

> 自然语言转SQL（NL2SQL）作为一种新的以模型为中心的范式，通过将自然语言查询转换为SQL命令，为非技术用户简化了数据库访问流程。近年来的技术进展，尤其是整合了检索增强生成（RAG）和思维链（CoT）推理的研究，在提升NL2SQL性能方面取得了显著突破。然而，大型语言模型（LLMs）在任务分解不准确和关键词提取错误等问题上仍存在瓶颈，这常常导致SQL生成出错。尽管现有数据集试图通过微调模型来缓解这些问题，但它们存在任务过度碎片化和缺乏领域特定关键词标注的问题，从而限制了其效果。为解决这些局限，我们提出了DeKeyNLU——一个包含1500个精心标注问答对的新型数据集，旨在优化任务分解并提高RAG管道的关键词提取精度。通过DeKeyNLU微调后，我们提出了DeKeySQL——一个基于RAG的NL2SQL管道，该管道采用三个独立模块分别负责用户问题理解、实体检索和生成，以提高SQL生成的准确性。我们在DeKeySQL的RAG管道中对多种模型配置进行了基准测试。实验结果表明，使用DeKeyNLU微调后，在BIRD（62.31%提升至69.10%）和Spider（84.2%提升至88.7%）开发数据集上的SQL生成准确率均显著提高。

> Natural Language to SQL (NL2SQL) provides a new model-centric paradigm that simplifies database access for non-technical users by converting natural language queries into SQL commands. Recent advancements, particularly those integrating Retrieval-Augmented Generation (RAG) and Chain-of-Thought (CoT) reasoning, have made significant strides in enhancing NL2SQL performance. However, challenges such as inaccurate task decomposition and keyword extraction by LLMs remain major bottlenecks, often leading to errors in SQL generation. While existing datasets aim to mitigate these issues by fine-tuning models, they struggle with over-fragmentation of tasks and lack of domain-specific keyword annotations, limiting their effectiveness. To address these limitations, we present DeKeyNLU, a novel dataset which contains 1,500 meticulously annotated QA pairs aimed at refining task decomposition and enhancing keyword extraction precision for the RAG pipeline. Fine-tuned with DeKeyNLU, we propose DeKeySQL, a RAG-based NL2SQL pipeline that employs three distinct modules for user question understanding, entity retrieval, and generation to improve SQL generation accuracy. We benchmarked multiple model configurations within DeKeySQL RAG pipeline. Experimental results demonstrate that fine-tuning with DeKeyNLU significantly improves SQL generation accuracy on both BIRD (62.31% to 69.10%) and Spider (84.2% to 88.7%) dev datasets.

[Arxiv](https://arxiv.org/abs/2509.14507)