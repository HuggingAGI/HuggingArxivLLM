# # OpenThoughts：推理模型的数据配方集锦

发布时间：2025年06月04日

`LLM应用

摘要主要讨论了推理模型的训练方法和性能提升，通过构建开源数据集和优化模型，推动了推理模型的应用和发展，属于LLM应用的范畴。` `人工智能`

> OpenThoughts: Data Recipes for Reasoning Models

# 摘要

> 推理模型在数学、代码和科学领域取得了显著进展，但在训练方法上仍有许多未解之谜。OpenThoughts 项目旨在打造开源数据集，推动推理模型的训练。基于 OpenThoughts2-1M 数据集，我们推出了 OpenThinker2-32B 模型，这是首个在公开推理数据上训练的模型，其性能在 AIME 和 LiveCodeBench 等基准测试中已达到 DeepSeek-R1-Distill-32B 的水平。通过 1,000 多次实验优化数据生成 pipeline，我们推出了 OpenThoughts3 数据集。将其扩展至 1.2M 示例，并以 QwQ-32B 作为教师模型，我们开发出了 OpenThinker3-7B，该模型在 AIME 2025、LiveCodeBench 06/24-01/25 和 GPQA Diamond 等任务中均达到了当前最优水平，准确率分别为 53%、51% 和 54%。所有资源均可在 https://openthoughts.ai 获取。

> Reasoning models have made rapid progress on many benchmarks involving math, code, and science. Yet, there are still many open questions about the best training recipes for reasoning since state-of-the-art models often rely on proprietary datasets with little to no public information available. To address this, the goal of the OpenThoughts project is to create open-source datasets for training reasoning models. After initial explorations, our OpenThoughts2-1M dataset led to OpenThinker2-32B, the first model trained on public reasoning data to match DeepSeek-R1-Distill-32B on standard reasoning benchmarks such as AIME and LiveCodeBench. We then improve our dataset further by systematically investigating each step of our data generation pipeline with 1,000+ controlled experiments, which led to OpenThoughts3. Scaling the pipeline to 1.2M examples and using QwQ-32B as teacher yields our OpenThinker3-7B model, which achieves state-of-the-art results: 53% on AIME 2025, 51% on LiveCodeBench 06/24-01/25, and 54% on GPQA Diamond. All of our datasets and models are available on https://openthoughts.ai.

[Arxiv](https://arxiv.org/abs/2506.04178)