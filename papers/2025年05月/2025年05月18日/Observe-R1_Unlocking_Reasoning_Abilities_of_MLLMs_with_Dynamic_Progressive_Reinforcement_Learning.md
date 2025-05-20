# Observe-R1：利用动态渐进强化学习释放多语言大语言模型的推理潜能

发布时间：2025年05月18日

`LLM应用` `人工智能`

> Observe-R1: Unlocking Reasoning Abilities of MLLMs with Dynamic Progressive Reinforcement Learning

# 摘要

> 强化学习 (RL) 在提升大型语言模型 (LLMs) 的推理能力方面展现出潜力。然而，将 RL 适应多模态数据和格式的具体挑战仍相对未被探索。在本研究中，我们提出了 Observe-R1，一个旨在增强多模态大型语言模型 (MLLMs) 推理能力的全新框架。我们从人类学习的进程——从简单到复杂，从容易到困难中汲取灵感，并为 MLLMs 提出了一种渐进式学习范式。为此，我们构建了 NeuraLadder 数据集，该数据集根据数据样本的难度和复杂性进行组织和采样，用于 RL 训练。为了处理多模态任务，我们引入了一种多模态格式约束，鼓励对图像进行仔细观察，从而提升了视觉能力，并生成了更清晰、更有条理的回应。此外，我们还实现了奖励机制，偏好在长度限制内提供简洁、正确的答案，并引入了动态加权机制，优先考虑不确定性和中等难度的问题，确保更具信息量的样本对训练产生更大影响。我们在 Qwen2.5-VL-3B 和 Qwen2.5-VL-7B 模型上，使用 NeuraLadder 数据集中的 20,000 个样本进行实验，结果显示 Observe-R1 在推理和通用基准测试中均超越了一系列更大规模的推理模型，推理链的清晰度和简洁性表现尤为突出。消融实验验证了我们策略的有效性，凸显了我们方法的鲁棒性和泛化能力。数据集和代码将在 https://github.com/zrguo/Observe-R1 上发布。

> Reinforcement Learning (RL) has shown promise in improving the reasoning abilities of Large Language Models (LLMs). However, the specific challenges of adapting RL to multimodal data and formats remain relatively unexplored. In this work, we present Observe-R1, a novel framework aimed at enhancing the reasoning capabilities of multimodal large language models (MLLMs). We draw inspirations from human learning progression--from simple to complex and easy to difficult, and propose a gradual learning paradigm for MLLMs. To this end, we construct the NeuraLadder dataset, which is organized and sampled according to the difficulty and complexity of data samples for RL training. To tackle multimodal tasks, we introduce a multimodal format constraint that encourages careful observation of images, resulting in enhanced visual abilities and clearer and more structured responses. Additionally, we implement a bonus reward system that favors concise, correct answers within a length constraint, alongside a dynamic weighting mechanism that prioritizes uncertain and medium-difficulty problems, ensuring that more informative samples have a greater impact on training. Our experiments with the Qwen2.5-VL-3B and Qwen2.5-VL-7B models on 20k samples from the NeuraLadder dataset show that Observe-R1 outperforms a series of larger reasoning models on both reasoning and general benchmarks, achieving superior clarity and conciseness in reasoning chains. Ablation studies validate the effectiveness of our strategies, highlighting the robustness and generalization of our approach. The dataset and code will be released at https://github.com/zrguo/Observe-R1.

[Arxiv](https://arxiv.org/abs/2505.12432)