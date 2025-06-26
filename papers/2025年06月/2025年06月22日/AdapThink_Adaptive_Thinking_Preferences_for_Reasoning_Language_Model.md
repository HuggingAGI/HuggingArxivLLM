# 自适应推理语言模型的思维偏好：AdapThink

发布时间：2025年06月22日

`LLM理论` `人工智能`

> AdapThink: Adaptive Thinking Preferences for Reasoning Language Model

# 摘要

> 基于强化学习 (RL) 的后训练显著提升了语言模型的复杂推理能力，同时促进了复杂的自我反思过程。然而，这种 ``慢思考'' 方法对推理效率提出了严峻挑战：模型可能在简单问题上耗费过多计算资源，而在处理复杂问题时过早转移推理方向。以往的机制通常依赖静态长度预算或预定义规则，缺乏对不同问题复杂性和模型能力演变的适应性。

为此，我们提出了 AdapThink，一个自适应后训练框架，旨在在保持推理语言模型性能的同时，促进更高效的思考。具体而言，AdapThink 包含两个关键机制：

1. 一种基于组的相对奖励函数，它利用模型置信度和响应的特性，动态调整与反思相关的过渡词的偏好，而无需依赖固定的长度偏好。
2. 一种考虑多样性的采样机制，通过熵引导的评分，平衡训练组的解决方案准确性和推理多样性。

在多个数学推理数据集上使用 DeepSeek 蒸馏模型进行的实验表明，AdapThink 在实现自适应推理模式和缓解低效推理方面具有显著优势。

> Reinforcement Learning (RL)-based post-training has significantly advanced the complex reasoning capabilities of language models, fostering sophisticated self-reflection processes. However, this ``slow thinking'' paradigm presents a critical challenge to reasoning efficiency: models may expend excessive computation on simple questions and shift reasoning prematurely for complex ones. Previous mechanisms typically rely on static length budgets or predefined rules, lacking the adaptability for varying question complexities and models' evolving capabilities. To this end, we propose AdapThink, an adaptive post-training framework designed to induce more efficient thinking while maintaining the performance of reasoning language models. Specifically, AdapThink incorporates two key mechanisms: 1) A group-relative reward function that leverages model confidence and response's characteristic to dynamically adjust the preference of reflection-related transition words without resorting to a fixed length preference. 2) A diversity-aware sampling mechanism that balances the training group's solution accuracy with reasoning diversity via an entropy-guided score. Experiments on several mathematical reasoning datasets with DeepSeek-distilled models demonstrate AdapThink's advantages in enabling adaptive reasoning patterns and mitigating the inefficiencies.

[Arxiv](https://arxiv.org/abs/2506.18237)