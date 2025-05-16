# 从文本中挖掘隐藏的思想：评估LLM推理的持续预训练与合成数据

发布时间：2025年05月15日

`LLM理论` `STEM`

> Mining Hidden Thoughts from Texts: Evaluating Continual Pretraining with Synthetic Data for LLM Reasoning

# 摘要

> 大型语言模型（LLMs）通过监督微调和强化学习在推理能力方面取得了显著提升。然而，这些方法在训练推理模型时主要适用于数学和编程等特定领域，这给训练数据的广度和可扩展性带来了根本性限制。相比之下，持续预训练（CPT）的优势在于不需要特定任务的信号。然而，如何有效地合成推理训练数据，以及这些数据如何影响广泛领域的效果仍 largely unexplored。本研究详细评估了推理CPT（一种使用合成数据重建文本背后隐藏思维过程的CPT形式），基于文本是作者思维过程结果的前提。具体而言，我们通过来自STEM和法律语料库的隐藏思维的合成数据，将推理CPT应用于Gemma2-9B，并将其与MMLU基准测试中的标准CPT进行比较。分析表明，推理CPT在所有评估领域中一致提高了性能。值得注意的是，一个领域中获得的推理技能能够有效迁移到其他领域；随着问题难度的增加，与传统方法的性能差距扩大，在最具挑战性的问题上提升高达8分。此外，通过隐藏思维训练的模型学会了根据问题难度调整推理深度。

> Large Language Models (LLMs) have demonstrated significant improvements in reasoning capabilities through supervised fine-tuning and reinforcement learning. However, when training reasoning models, these approaches are primarily applicable to specific domains such as mathematics and programming, which imposes fundamental constraints on the breadth and scalability of training data. In contrast, continual pretraining (CPT) offers the advantage of not requiring task-specific signals. Nevertheless, how to effectively synthesize training data for reasoning and how such data affect a wide range of domains remain largely unexplored. This study provides a detailed evaluation of Reasoning CPT, a form of CPT that uses synthetic data to reconstruct the hidden thought processes underlying texts, based on the premise that texts are the result of the author's thinking process. Specifically, we apply Reasoning CPT to Gemma2-9B using synthetic data with hidden thoughts derived from STEM and Law corpora, and compare it to standard CPT on the MMLU benchmark. Our analysis reveals that Reasoning CPT consistently improves performance across all evaluated domains. Notably, reasoning skills acquired in one domain transfer effectively to others; the performance gap with conventional methods widens as problem difficulty increases, with gains of up to 8 points on the most challenging problems. Furthermore, models trained with hidden thoughts learn to adjust the depth of their reasoning according to problem difficulty.

[Arxiv](https://arxiv.org/abs/2505.10182)