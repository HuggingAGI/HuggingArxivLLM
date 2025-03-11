# Vision-R1：提升多模态大型语言模型的推理能力

发布时间：2025年03月09日

`LLM应用

摘要中提到，论文探讨了如何利用强化学习提升多模态大型语言模型的推理能力，并提出了Vision-R1模型。这属于对大型语言模型的具体应用和性能提升，因此归类为LLM应用。` `人工智能`

> Vision-R1: Incentivizing Reasoning Capability in Multimodal Large Language Models

# 摘要

> DeepSeek-R1-Zero 通过强化学习（RL）成功展示了大型语言模型（LLMs）推理能力的涌现。受此启发，我们探索了如何利用 RL 提升多模态大型语言模型（MLLMs）的推理能力。然而，由于缺乏高质量的多模态推理数据，直接使用 RL 训练难以激活多模态模型的复杂推理能力，如质疑和反思。为解决这一问题，我们提出了 Vision-R1，一款具备推理能力的多模态大型语言模型，旨在提升多模态推理能力。

具体而言，我们通过现有 MLLM 和 DeepSeek-R1，借助模态间桥梁和数据过滤，构建了一个无需人工标注的高质量多模态 CoT 数据集，最终获得包含 20 万条数据的 Vision-R1-cold 数据集，作为 Vision-R1 的冷启动初始化数据。为缓解冷启动后过度思考的优化挑战，我们提出了渐进式思考抑制训练（PTST）策略，并采用带有硬格式化结果奖励函数的组相对策略优化（GRPO），在包含 1 万条数据的多模态数学数据集上逐步优化模型学习正确和复杂推理过程的能力。

综合实验表明，我们的模型在各种多模态数学推理基准测试中平均提升了约【数学公式】6%。Vision-R1-7B 在广泛使用的 MathVista 基准测试中达到了 73.5% 的准确率，仅比领先的推理模型 OpenAI O1 低 0.4%。数据集和代码将在 https://github.com/Osilly/Vision-R1 上发布。

> DeepSeek-R1-Zero has successfully demonstrated the emergence of reasoning capabilities in LLMs purely through Reinforcement Learning (RL). Inspired by this breakthrough, we explore how RL can be utilized to enhance the reasoning capability of MLLMs. However, direct training with RL struggles to activate complex reasoning capabilities such as questioning and reflection in MLLMs, due to the absence of substantial high-quality multimodal reasoning data. To address this issue, we propose the reasoning MLLM, Vision-R1, to improve multimodal reasoning capability. Specifically, we first construct a high-quality multimodal CoT dataset without human annotations by leveraging an existing MLLM and DeepSeek-R1 through modality bridging and data filtering to obtain a 200K multimodal CoT dataset, Vision-R1-cold dataset. It serves as cold-start initialization data for Vision-R1. To mitigate the optimization challenges caused by overthinking after cold start, we propose Progressive Thinking Suppression Training (PTST) strategy and employ Group Relative Policy Optimization (GRPO) with the hard formatting result reward function to gradually refine the model's ability to learn correct and complex reasoning processes on a 10K multimodal math dataset. Comprehensive experiments show our model achieves an average improvement of $\sim$6% across various multimodal math reasoning benchmarks. Vision-R1-7B achieves a 73.5% accuracy on the widely used MathVista benchmark, which is only 0.4% lower than the leading reasoning model, OpenAI O1. The datasets and code will be released in: https://github.com/Osilly/Vision-R1 .

[Arxiv](https://arxiv.org/abs/2503.06749)