# 逐步提升！基于课程学习框架优化大型语言模型知识蒸馏

发布时间：2025年06月05日

`LLM应用` `机器学习` `模型压缩`

> Being Strong Progressively! Enhancing Knowledge Distillation of Large Language Models through a Curriculum Learning Framework

# 摘要

> 知识蒸馏（KD）通过将大型语言模型（LLMs）的能力迁移到更小的学生模型，实现模型压缩的同时保持性能，同时降低了推理成本和内存占用。然而，现有的LLMs蒸馏方法往往无法有效解决学生模型在训练过程中出现的分布偏移问题，导致灾难性遗忘、模式坍缩以及训练与推理不匹配等挑战。为应对这些难题，我们提出了一种受“渐进超载”（POCL）训练理念启发的新型即插即用课程学习框架，该框架可轻松嵌入现有白盒KD流程，且几乎不增加计算负担。框架包含两大核心模块：（1）难度评估器，用于对训练样本按难度从低到高进行排序与分组；（2）训练调度器，在固定间隔内逐步将这些分组样本引入蒸馏流程，并采用温度逐步升高的损失函数。通过从简单样本入手并循序渐进地提升难度，该方法显著增强了学习过程的稳定性和效率。实验结果表明，在多种白盒KD方法和模型架构下，POCL均能有效提升蒸馏模型的性能。我们的研究证明了在知识蒸馏中对训练样本进行排序的重要性。这项工作不仅为LLMs蒸馏提供了新的解决方案，更为构建高效稳定的训练数据结构提供了重要参考。

> Knowledge Distillation (KD) compresses large language models (LLMs) by transferring the teacher model's capabilities to a smaller student model, reducing inference cost and memory usage while maintaining performance. However, existing KD methods for LLMs often fail to prevent significant shifts in the student model's distribution during training, leading to issues such as catastrophic forgetting, mode collapse, and training-inference mismatch. To address these challenges, we propose a novel, plug-in curriculum learning framework inspired by the strength training principle of "progressive overload" (POCL), which can be seamlessly integrated into existing white-box KD approaches with minimal computational overhead. The framework comprises two core components: (1) a difficulty measurer that ranks and partitions training samples from easy to hard, and (2) a training scheduler that incrementally introduces these subsets into the distillation process at fixed intervals while applying loss functions with progressively rising temperatures. By starting with the easiest samples and progressively increasing the difficulty, the approach enhances both the stability and efficiency of learning. Extensive experiments in instruction-following settings demonstrate that POCL consistently improves the performance of distilled student models across various white-box KD methods and model families. Our findings highlight the effectiveness of sorted training samples in KD for LLMs. More generally, our work demonstrates how to structure training data within the KD process to enhance the stability and performance of distilled LLMs.

[Arxiv](https://arxiv.org/abs/2506.05695)