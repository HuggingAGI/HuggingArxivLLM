# # 优化捷克语 GEC：通过多实验方法探索见解

发布时间：2025年06月27日

`LLM应用

理由：该论文探讨了大型语言模型（LLMs）在语法错误修正任务中的应用，展示了其在实际任务中的性能和效果。`

> Refining Czech GEC: Insights from a Multi-Experiment Approach

# 摘要

> 我们提出了一种针对捷克语的语法错误修正（GEC）系统，达到了最先进的水平。该系统基于Transformer架构的神经网络翻译方法，其核心是实时合成生成流水线，能够动态地通过语言无关和捷克语特定的错误为句子添加人工错误。我们进行了全面的实验，研究了捷克语GEC语料库作为合成错误引入的基础、多种错误生成策略、领域平衡、分词粒度、模型规模，以及在微调过程中的数据扩展。此外，我们还评估了大型语言模型（LLMs）在捷克语GEC任务中的表现，分别在终端用户和专家微调场景下进行了测试。我们表现最佳的模型在性能和计算效率方面均优于其他方法。源代码和训练好的模型链接可在https://github.com/ufal/tsd2025-gec上获取。

> We present a grammar error correction (GEC) system that achieves state of the art for the Czech language. Our system is based on a neural network translation approach with the Transformer architecture, and its key feature is its real-time synthetic generation pipeline, which dynamically augments sentences with artificial errors by introducing both language-agnostic and Czech-specific errors. We conduct a comprehensive series of experiments, investigating the Czech GEC corpora as bases for synthetic error introduction, several error generation strategies, domain balancing, tokenization granularity, model size, and data scaling during fine-tuning. Additionally, we evaluate the performance of large language models (LLMs) on Czech GEC in both end-user and expert fine-tuning scenarios. Our best-performing model is superior both in performance and computational efficiency. The source code and the trained model links are available on https://github.com/ufal/tsd2025-gec.

[Arxiv](https://arxiv.org/abs/2506.22402)