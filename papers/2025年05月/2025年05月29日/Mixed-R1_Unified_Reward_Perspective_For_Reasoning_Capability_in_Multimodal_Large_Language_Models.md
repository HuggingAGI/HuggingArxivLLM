# Mixed-R1: 统一奖励视角下的多模态大型语言模型推理能力研究

发布时间：2025年05月29日

`LLM理论` `大型语言模型`

> Mixed-R1: Unified Reward Perspective For Reasoning Capability in Multimodal Large Language Models

# 摘要

> 最近关于大型语言模型 (LLMs) 的研究通过强化学习 (RL) 成功展示了推理能力的出现。尽管现有研究利用组相对策略优化 (GRPO) 对LLMs进行后训练，但它们仅专注于特定领域，如基础任务、数学问题或图表分析。目前尚无研究能够利用多源LLM任务实现稳定的强化学习。

为解决这一问题，我们提出了一种统一的视角和Mixed-R1框架，该框架包含混合奖励函数设计 (Mixed-Reward) 和混合后训练数据集 (Mixed-45K)。我们首先设计了一个数据引擎来构建Mixed-45K后训练数据集。随后，我们提出了Mixed-Reward设计，包含以下四种奖励函数：

1. 匹配奖励：用于二元答案或选择题  
2. 图表奖励：用于图表感知数据集  
3. IoU奖励：用于基础任务  
4. 开放奖励：用于长文本响应，如字幕数据集  

针对长文本内容，我们提出了一种新的开放奖励——双向最大平均相似度 (BMAS)，通过生成响应和真实答案之间的分词器嵌入匹配实现。实验表明，我们的方法在Qwen2.5-VL和Intern-VL等不同规模的LLMs上均表现出色。我们的数据集和模型已开源，可在https://github.com/xushilin1/mixed-r1获取。

> Recent works on large language models (LLMs) have successfully demonstrated the emergence of reasoning capabilities via reinforcement learning (RL). Although recent efforts leverage group relative policy optimization (GRPO) for MLLMs post-training, they constantly explore one specific aspect, such as grounding tasks, math problems, or chart analysis. There are no works that can leverage multi-source MLLM tasks for stable reinforcement learning. In this work, we present a unified perspective to solve this problem. We present Mixed-R1, a unified yet straightforward framework that contains a mixed reward function design (Mixed-Reward) and a mixed post-training dataset (Mixed-45K). We first design a data engine to select high-quality examples to build the Mixed-45K post-training dataset. Then, we present a Mixed-Reward design, which contains various reward functions for various MLLM tasks. In particular, it has four different reward functions: matching reward for binary answer or multiple-choice problems, chart reward for chart-aware datasets, IoU reward for grounding problems, and open-ended reward for long-form text responses such as caption datasets. To handle the various long-form text content, we propose a new open-ended reward named Bidirectional Max-Average Similarity (BMAS) by leveraging tokenizer embedding matching between the generated response and the ground truth. Extensive experiments show the effectiveness of our proposed method on various MLLMs, including Qwen2.5-VL and Intern-VL on various sizes. Our dataset and model are available at https://github.com/xushilin1/mixed-r1.

[Arxiv](https://arxiv.org/abs/2505.24164)