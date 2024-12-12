# 借助大型语言模型的微调来推动单任务和多任务文本分类

发布时间：2024年12月11日

`LLM应用` `文本分类`

> Advancing Single- and Multi-task Text Classification through Large Language Model Fine-tuning

# 摘要

> 无论是仅编码器模型（如 BERT、RoBERTa），还是大型语言模型（如 Llama3），都已被广泛应用于文本分类任务。然而，对于基于编码器的模型和 LLMs 在文本分类中的性能比较，尤其是涉及微调的情况，目前缺乏系统研究。本研究运用了规模和架构各异的多种模型与方法，涵盖了微调及预训练方式。我们先是在 20 Newsgroups（20NG）和 MASSIVE 数据集上评估了这些 LLMs 的表现，并与仅编码器的 RoBERTa 模型作对比。另外，我们利用来自两个数据集的数据，将多个分类任务（包括意图检测和槽填充）整合到一个模型中，以此探究这两类模型的多任务能力。结果显示，在各类分类任务和数据集中，完全微调的 Llama3-70B 模型的表现优于 RoBERTa-large 及其他解码器 LLMs。而且，整合的多任务微调 LLMs 在两个数据集的两个任务中的表现与双模型设置相当。总之，我们的研究为仅编码器模型和 LLMs 在文本分类任务上提供了全面的基准，并展示了一种将两个或更多完全微调的解码器 LLMs 组合起来以降低延迟并实现同等性能的方法。

> Both encoder-only models (e.g., BERT, RoBERTa) and large language models (LLMs, e.g., Llama3) have been widely used for text classification tasks. However, there is a lack of systematic studies comparing the performance of encoder-based models and LLMs in text classification, particularly when fine-tuning is involved. This study employed a diverse range of models and methods, varying in size and architecture, and including both fine-tuned and pre-trained approaches. We first assessed the performances of these LLMs on the 20 Newsgroups (20NG) and MASSIVE datasets, comparing them to encoder-only RoBERTa models. Additionally, we explored the multi-task capabilities of both model types by combining multiple classification tasks, including intent detection and slot-filling, into a single model using data from both datasets. Our results indicate that fully fine-tuned Llama3-70B models outperform RoBERTa-large and other decoder LLMs across various classification tasks and datasets. Moreover, the consolidated multi-task fine-tuned LLMs matched the performance of dual-model setups in both tasks across both datasets. Overall, our study provides a comprehensive benchmark of encoder-only and LLM models on text classification tasks and demonstrates a method to combine two or more fully fine-tuned decoder LLMs for reduced latency and equivalent performance.

[Arxiv](https://arxiv.org/abs/2412.08587)