# 一个任务向量远远不够：大规模研究上下文学习

发布时间：2025年05月29日

`LLM应用` `机器学习`

> One Task Vector is not Enough: A Large-Scale Study for In-Context Learning

# 摘要

> ICL 赋能大型语言模型 (LLMs) 通过少量示例快速适应新任务，其中任务向量（特定隐藏状态激活）被认为是编码任务信息的核心。然而，现有研究受限于小型基准测试，这限制了对 ICL 的全面分析。我们引入了全新数据集 QuiteAFew，包含 3096 个多样化少量示例任务，每个任务包含 30 个输入-输出对，这些数据源自 Alpaca 数据集。在 Llama-3-8B 上对 QuiteAFew 进行的实验揭示了以下几点：(1) 任务向量的性能在第 15 层时达到峰值，(2) 不同任务类型的效果差异显著，以及 (3) 复杂任务依赖于多个特定于子任务的向量，而非单一向量，这表明任务知识的分布式表示。

> In-context learning (ICL) enables Large Language Models (LLMs) to adapt to new tasks using few examples, with task vectors - specific hidden state activations - hypothesized to encode task information. Existing studies are limited by small-scale benchmarks, restricting comprehensive analysis. We introduce QuiteAFew, a novel dataset of 3,096 diverse few-shot tasks, each with 30 input-output pairs derived from the Alpaca dataset. Experiments with Llama-3-8B on QuiteAFew reveal: (1) task vector performance peaks at an intermediate layer (e.g., 15th), (2) effectiveness varies significantly by task type, and (3) complex tasks rely on multiple, subtask-specific vectors rather than a single vector, suggesting distributed task knowledge representation.

[Arxiv](https://arxiv.org/abs/2505.23911)