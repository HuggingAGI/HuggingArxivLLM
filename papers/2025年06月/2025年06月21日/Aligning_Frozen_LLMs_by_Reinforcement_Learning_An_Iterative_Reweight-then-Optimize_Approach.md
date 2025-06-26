# 强化学习对齐冻结LLMs：迭代重加权优化方法

发布时间：2025年06月21日

`LLM理论

论文摘要：对齐大型语言模型（LLMs）与人类偏好通常依赖强化学习人类反馈（RLHF）和决策优化（DPO）等微调方法。这些方法直接优化模型参数，因此无法在测试阶段用于提升性能，也不适用于模型权重不可访问的场景。相比之下，测试时间方法通过奖励函数引导输出质量，绕过了权重更新，但其高昂的推理成本和基于不完美奖励或价值函数的单次指导，往往导致次优输出。本研究提出了一种名为迭代重权优化（IRO）的强化学习（RL）框架，能够在不修改模型参数的情况下，对冻结的基础模型进行强化学习风格的对齐。在训练中，每个迭代周期从基础模型采样候选输出，利用当前价值函数重采样，并训练轻量化价值函数指导下一轮解码。测试时，通过基于搜索的优化流程，利用价值函数引导基础模型生成。值得注意的是，用户可将IRO应用于自有数据集上的模型对齐，类似于OpenAI的强化微调（RFT），但无需访问模型权重。

LLM理论` `人工智能` `机器学习`

> Aligning Frozen LLMs by Reinforcement Learning: An Iterative Reweight-then-Optimize Approach

# 摘要

> 对齐大型语言模型（LLMs）与人类偏好通常依赖强化学习人类反馈（RLHF）和决策优化（DPO）等微调方法。这些方法直接优化模型参数，因此无法在测试阶段用于提升性能，也不适用于模型权重不可访问的场景。相比之下，测试时间方法通过奖励函数引导输出质量，绕过了权重更新，但其高昂的推理成本和基于不完美奖励或价值函数的单次指导，往往导致次优输出。本研究提出了一种名为迭代重权优化（IRO）的强化学习（RL）框架，能够在不修改模型参数的情况下，对冻结的基础模型进行强化学习风格的对齐。在训练中，每个迭代周期从基础模型采样候选输出，利用当前价值函数重采样，并训练轻量化价值函数指导下一轮解码。测试时，通过基于搜索的优化流程，利用价值函数引导基础模型生成。值得注意的是，用户可将IRO应用于自有数据集上的模型对齐，类似于OpenAI的强化微调（RFT），但无需访问模型权重。

> Aligning large language models (LLMs) with human preferences usually requires fine-tuning methods such as RLHF and DPO. These methods directly optimize the model parameters, so they cannot be used in test-time to improve model performance, nor are they applicable when the model weights are not accessible. In contrast, test-time methods sidestep weight updates by leveraging reward functions to guide and improve output quality. However, they incur high inference costs, and their one-shot guidance is often based on imperfect reward or value functions, leading to suboptimal outputs. In this work, we present a method named Iterative Reweight-then-Optimize (IRO), a reinforcement learning (RL) framework that performs RL-style alignment of the (frozen) base model without touching its parameters. During training, each iteration (i) samples candidates from the base model, (ii) resamples using current value functions, and (iii) trains a new lightweight value function that guides the next decoding pass. At test time, the value functions are used to guide the base model generation via a search-based optimization process. Notably, users can apply IRO to align a model on their own dataset, similar to OpenAI's reinforcement fine-tuning (RFT), but without requiring access to the model weights.

[Arxiv](https://arxiv.org/abs/2506.17828)