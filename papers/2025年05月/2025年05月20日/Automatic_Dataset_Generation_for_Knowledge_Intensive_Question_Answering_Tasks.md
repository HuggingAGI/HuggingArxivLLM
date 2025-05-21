# 知识密集型问答任务的自动数据集生成

发布时间：2025年05月20日

`LLM应用` `问答系统`

> Automatic Dataset Generation for Knowledge Intensive Question Answering Tasks

# 摘要

> 问答系统（QA系统）的核心任务是从知识库中精准搜索答案。然而，现有的问答系统在面对需要复杂推理或实时知识整合的查询时表现欠佳。为了解决这一问题，研究者通常会采用基于数据源的检索技术，例如基于检索增强生成（RAG）的方法。尽管如此，RAG在处理复杂推理和多个信息源之间的逻辑关联方面仍存在局限性。为此，本文提出了一种创新方法——通过自动生成基于上下文的问答对来增强大型语言模型（LLMs）在知识密集型问答任务中的表现。这种方法巧妙地利用LLMs生成微调数据，不仅减少了对人工标注的依赖，还显著提升了模型的理解和推理能力。我们的系统包含两个核心模块：自动问答生成器和模型微调器，通过困惑度、ROUGE、BLEU和BERTScore等指标进行评估。经过全面的实验验证，该方法在逻辑连贯性和事实准确性方面均取得了显著提升，为开发更加灵活和智能的AI系统提供了重要启示。值得注意的是，Mistral-7b-v0.3在BERT F1、BLEU和ROUGE评分上分别为0.858、0.172和0.260，相较于Llama-3-8b的0.836、0.083和0.139，表现更加出色。

> A question-answering (QA) system is to search suitable answers within a knowledge base. Current QA systems struggle with queries requiring complex reasoning or real-time knowledge integration. They are often supplemented with retrieval techniques on a data source such as Retrieval-Augmented Generation (RAG). However, RAG continues to face challenges in handling complex reasoning and logical connections between multiple sources of information. A novel approach for enhancing Large Language Models (LLMs) in knowledge-intensive QA tasks is presented through the automated generation of context-based QA pairs. This methodology leverages LLMs to create fine-tuning data, reducing reliance on human labelling and improving model comprehension and reasoning capabilities. The proposed system includes an automated QA generator and a model fine-tuner, evaluated using perplexity, ROUGE, BLEU, and BERTScore. Comprehensive experiments demonstrate improvements in logical coherence and factual accuracy, with implications for developing adaptable Artificial Intelligence (AI) systems. Mistral-7b-v0.3 outperforms Llama-3-8b with BERT F1, BLEU, and ROUGE scores 0.858, 0.172, and 0.260 of for the LLM generated QA pairs compared to scores of 0.836, 0.083, and 0.139 for the human annotated QA pairs.

[Arxiv](https://arxiv.org/abs/2505.14212)