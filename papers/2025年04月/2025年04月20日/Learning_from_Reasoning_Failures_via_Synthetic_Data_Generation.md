# 利用合成数据从推理失败中学习

发布时间：2025年04月20日

`LLM应用` `生成式AI` `多模态模型`

> Learning from Reasoning Failures via Synthetic Data Generation

# 摘要

> 在生成式 AI 的性能提升方面，使用合成数据训练模型已成为一种日益重要的策略。由于与纯语言数据相比，高质量的图像-文本配对数据相对稀缺，因此这种方法对大型多模态模型（LMMs）尤其有用。尽管已经提出了多种生成大规模多模态数据集的方法，但它们并未针对特定的 LMMs 推理能力缺陷来定制合成数据，而这些 LMMs 将使用生成的数据集进行训练。相比之下，人类通常会通过寻找与之前推理失败类型相关的示例来以更高效的方式学习。受到这一观察的启发，我们提出了一种新的合成数据生成方法，该方法基于对现有 LMM 推理失败的分析。我们的方法利用前沿模型自动分析较弱 LMM 产生的错误，并提出新的示例，这些示例可以通过额外的训练来纠正推理失败，然后进一步筛选以确保高质量。我们使用我们的方法生成了一个包含超过 553,000 个示例的大型多模态指令微调数据集，并进行了广泛实验，证明了其对提升 LMMs 在多个下游任务上性能的实用性。我们的结果显示，使用我们的合成数据训练的模型甚至可以超越在同等数量额外真实数据上训练的 LMMs 的性能，这证明了针对 LMMs 特定推理失败模式生成合成数据的高价值。我们计划公开发布我们的数据集和代码。

> Training models on synthetic data has emerged as an increasingly important strategy for improving the performance of generative AI. This approach is particularly helpful for large multimodal models (LMMs) due to the relative scarcity of high-quality paired image-text data compared to language-only data. While a variety of methods have been proposed for generating large multimodal datasets, they do not tailor the synthetic data to address specific deficiencies in the reasoning abilities of LMMs which will be trained with the generated dataset. In contrast, humans often learn in a more efficient manner by seeking out examples related to the types of reasoning where they have failed previously. Inspired by this observation, we propose a new approach for synthetic data generation which is grounded in the analysis of an existing LMM's reasoning failures. Our methodology leverages frontier models to automatically analyze errors produced by a weaker LMM and propose new examples which can be used to correct the reasoning failure via additional training, which are then further filtered to ensure high quality. We generate a large multimodal instruction tuning dataset containing over 553k examples using our approach and conduct extensive experiments demonstrating its utility for improving the performance of LMMs on multiple downstream tasks. Our results show that models trained on our synthetic data can even exceed the performance of LMMs trained on an equivalent amount of additional real data, demonstrating the high value of generating synthetic data targeted to specific reasoning failure modes in LMMs. We will make our dataset and code publicly available.

[Arxiv](https://arxiv.org/abs/2504.14523)