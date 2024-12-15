# 提升小规模大型语言模型在推理任务中的函数调用能力

发布时间：2024年10月24日

`LLM应用` `逻辑推理`

> Improving Small-Scale Large Language Models Function Calling for Reasoning Tasks

# 摘要

> 近期，大型语言模型（LLMs）取得了进展，在自然语言理解和生成方面展现出非凡能力。尽管这些模型在一般复杂推理任务中表现优异，但在数学问题解决和逻辑推理方面仍存在挑战。为解决这些局限，研究人员探索了函数调用能力，让 LLMs 能够执行所提供的函数，并利用其输出完成任务。然而，对于大规模 LLMs 而言，专注于特定任务的使用效率可能很低，因为在训练和推理阶段，它们所需的计算资源成本高昂。本研究为函数调用中的小型语言模型训练引入了新框架，重点关注特定的逻辑和数学推理任务。该方法旨在通过函数调用提升小规模模型在这些任务上的性能，确保高精度。我们的框架采用一个代理，给定一个问题和一组可调用函数，将可用函数的描述和示例注入提示，并在逐步推理链中管理它们的调用，以此来查询 LLMs。这个过程用于从大规模 LLMs 创建正确和错误推理链聊天完成的数据集。该数据集用于使用基于人类反馈的强化学习（RLHF）训练较小的 LLMs，尤其采用了直接偏好优化（DPO）技术。实验结果表明，所提出的方法如何在模型大小和性能之间权衡，提高了小规模模型在推理任务中的函数调用能力。

> Recent advancements in Large Language Models (LLMs) have demonstrated exceptional capabilities in natural language understanding and generation. While these models excel in general complex reasoning tasks, they still face challenges in mathematical problem-solving and logical reasoning. To address these limitations, researchers have explored function calling abilities, allowing LLMs to execute provided functions and utilize their outputs for task completion. However, concentrating on specific tasks can be very inefficient for large-scale LLMs to be used, because of the expensive cost of training and inference stages they need in terms of computational resources. This study introduces a novel framework for training smaller language models in function calling, focusing on specific logical and mathematical reasoning tasks. The approach aims to improve performances of small-scale models for these tasks using function calling, ensuring a high level of accuracy. Our framework employs an agent that, given a problem and a set of callable functions, queries the LLM by injecting a description and examples of the usable functions into the prompt and managing their calls in a step-by-step reasoning chain. This process is used to create a dataset of correct and incorrect reasoning chain chat completions from a large-scale LLM. This dataset is used to train a smaller LLM using Reinforcement Learning from Human Feedback (RLHF), specifically employing the Direct Preference Optimization (DPO) technique. Experimental results demonstrate how the proposed approach balances the trade-off between model size and performance, improving the ability of function calling for reasoning tasks, in smaller models.

[Arxiv](https://arxiv.org/abs/2410.18890)