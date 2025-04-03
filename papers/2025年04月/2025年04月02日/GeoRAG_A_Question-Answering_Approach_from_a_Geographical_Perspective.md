# GeoRAG：地理视角下的问题回答方法

发布时间：2025年04月02日

`RAG` `问答系统`

> GeoRAG: A Question-Answering Approach from a Geographical Perspective

# 摘要

> 地理问答（GeoQA）致力于通过自然语言处理地理领域的问题，以满足复杂需求并提升信息检索效率。然而，传统问答系统在理解能力、检索精度、交互性和复杂任务处理方面存在诸多不足，严重制约了信息获取的准确性。本研究推出了GeoRAG——一个融合领域特定微调、提示工程与检索增强生成（RAG）技术的知识增强问答框架，旨在显著提升地理知识检索的精准度和用户互动体验。

该框架的核心由四大组件构成：首先，构建了一个基于3267个地理相关语料库（包括研究论文、专著和技术报告）的结构化知识库，通过多智能体方法从语义理解、空间位置、几何形态、属性特征、特征关系、演化过程及运行机制七大维度进行分类整理，最终生成了145,234个分类条目和875,432个多维度问答对。其次，开发了一个基于BERT-Base-Chinese的多标签文本分类器，经过专业训练，能够通过对地理维度的精准分类来解析查询类型。第三，设计了一个检索评估器，通过问答对数据评估查询与文档的相关性，从而优化检索精度。最后，创新性地引入了GeoPrompt模板，通过动态整合用户查询与检索信息，并结合维度特定的提示策略，显著提升了系统响应的质量。

实验结果表明，相较于传统RAG方法，GeoRAG在多个基础模型上均展现出显著优势，充分证明了其优异的泛化能力。本研究不仅为大型语言模型在地理领域的应用开辟了全新范式，更为提升地理问答系统在实际应用中的可扩展性和准确性提供了重要参考，标志着地理人工智能领域的重要进展。

> Geographic Question Answering (GeoQA) addresses natural language queries in geographic domains to fulfill complex user demands and improve information retrieval efficiency. Traditional QA systems, however, suffer from limited comprehension, low retrieval accuracy, weak interactivity, and inadequate handling of complex tasks, hindering precise information acquisition. This study presents GeoRAG, a knowledge-enhanced QA framework integrating domain-specific fine-tuning and prompt engineering with Retrieval-Augmented Generation (RAG) technology to enhance geographic knowledge retrieval accuracy and user interaction. The methodology involves four components: (1) A structured geographic knowledge base constructed from 3267 corpora (research papers, monographs, and technical reports), categorized via a multi-agent approach into seven dimensions: semantic understanding, spatial location, geometric morphology, attribute characteristics, feature relationships, evolutionary processes, and operational mechanisms. This yielded 145234 classified entries and 875432 multi-dimensional QA pairs. (2) A multi-label text classifier based on BERT-Base-Chinese, trained to analyze query types through geographic dimension classification. (3) A retrieval evaluator leveraging QA pair data to assess query-document relevance, optimizing retrieval precision. (4) GeoPrompt templates engineered to dynamically integrate user queries with retrieved information, enhancing response quality through dimension-specific prompting. Comparative experiments demonstrate GeoRAG's superior performance over conventional RAG across multiple base models, validating its generalizability. This work advances geographic AI by proposing a novel paradigm for deploying large language models in domain-specific contexts, with implications for improving GeoQA systems scalability and accuracy in real-world applications.

[Arxiv](https://arxiv.org/abs/2504.01458)