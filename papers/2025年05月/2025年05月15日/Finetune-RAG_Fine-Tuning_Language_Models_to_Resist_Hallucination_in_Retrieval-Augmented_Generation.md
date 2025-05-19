# # Finetune-RAG — 防止检索增强生成中的幻觉：微调语言模型的新方法

发布时间：2025年05月15日

`RAG` `信息检索`

> Finetune-RAG: Fine-Tuning Language Models to Resist Hallucination in Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）已成为提升大型语言模型（LLMs）事实准确性的强大框架，通过将模型输出与检索到的文档相结合。然而，完美检索相关信息仍具挑战，不相关内容传递给LLM可能导致幻觉。本研究提出Finetune-RAG，这是一种简单有效的微调方法，首次构建模拟现实不完美性的RAG训练数据集。实验结果表明，Finetune-RAG将事实准确性较基础模型提升了21.2%。我们还推出Bench-RAG，这是一个基于LLM作为评判者的评估流水线，可在现实不完美检索场景下对模型进行压力测试。我们的代码库和数据集已完全开源，供社区使用。

> Retrieval-Augmented Generation (RAG) has emerged as a powerful framework to improve factuality in large language models (LLMs) by grounding their outputs in retrieved documents. However, ensuring perfect retrieval of relevant information remains challenging, and when irrelevant content is passed downstream to an LLM, it can lead to hallucinations. In this work, we propose Finetune-RAG, a simple and effective fine-tuning approach that features the first-of-its-kind RAG training dataset constructed to mimic real-world imperfections. Experimental results show that Finetune-RAG improves factual accuracy by 21.2% over the base model. We also propose a Bench-RAG, an LLM-as-a-judge evaluation pipeline that stress tests models under realistic imperfect retrieval scenarios. Our codebase and dataset are fully open sourced for community use.

[Arxiv](https://arxiv.org/abs/2505.10792)