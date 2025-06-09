# 路径与推理：通过强化模型路由器扩展大型语言模型推理能力

发布时间：2025年06月06日

`LLM应用` `大型语言模型`

> Route-and-Reason: Scaling Large Language Model Reasoning with Reinforced Model Router

# 摘要

> 多步推理通过将复杂任务分解为中间步骤（无论是显式还是隐式）已被证明是提升大型语言模型 (LLMs) 问题解决能力的关键。通过在测试时通过更深入的思考过程或更广泛的探索来延长推理链，可以进一步提高性能，但通常会因令牌使用量的激增而产生巨大成本。然而，许多推理步骤相对简单，可以通过更高效的小规模语言模型 (SLMs) 处理。这促使我们采用混合方法，将子任务分配给不同容量的模型。然而，实现这种协作需要准确的任务分解和难度感知的子任务分配，这极具挑战性。

为了解决这一问题，我们提出了 R2-Reasoner，一个全新的框架，它通过基于估计复杂性的动态路由在异构 LLM 之间实现协作推理。我们框架的核心是一个强化模型路由器，由任务分解器和子任务分配器组成。任务分解器将复杂的输入查询分解为逻辑有序的子任务，而子任务分配器将每个子任务分配给最合适模型，从轻量级 SLMs 到强大的 LLMs，平衡准确性和效率。

为了训练这个路由器，我们引入了一个分阶段的管道，结合了特定任务数据集上的监督微调和组相对策略优化算法，通过迭代强化学习实现自我监督优化。在四个具有挑战性的基准测试中进行的广泛实验表明，R2-Reasoner 在保持或超越基线准确性的同时，将 API 成本降低了 86.85%。我们的框架为更经济高效和适应性的 LLM 推理铺平了道路。代码在 https://anonymous.4open.science/r/R2_Reasoner 开源。

> Multi-step reasoning has proven essential for enhancing the problem-solving capabilities of Large Language Models (LLMs) by decomposing complex tasks into intermediate steps, either explicitly or implicitly. Extending the reasoning chain at test time through deeper thought processes or broader exploration, can furthur improve performance, but often incurs substantial costs due to the explosion in token usage. Yet, many reasoning steps are relatively simple and can be handled by more efficient smaller-scale language models (SLMs). This motivates hybrid approaches that allocate subtasks across models of varying capacities. However, realizing such collaboration requires accurate task decomposition and difficulty-aware subtask allocation, which is challenging. To address this, we propose R2-Reasoner, a novel framework that enables collaborative reasoning across heterogeneous LLMs by dynamically routing sub-tasks based on estimated complexity. At the core of our framework is a Reinforced Model Router, composed of a task decomposer and a subtask allocator. The task decomposer segments complex input queries into logically ordered subtasks, while the subtask allocator assigns each subtask to the most appropriate model, ranging from lightweight SLMs to powerful LLMs, balancing accuracy and efficiency. To train this router, we introduce a staged pipeline that combines supervised fine-tuning on task-specific datasets with Group Relative Policy Optimization algorithm, enabling self-supervised refinement through iterative reinforcement learning. Extensive experiments across four challenging benchmarks demonstrate that R2-Reasoner reduces API costs by 86.85% while maintaining or surpassing baseline accuracy. Our framework paves the way for more cost-effective and adaptive LLM reasoning. The code is open-source at https://anonymous.4open.science/r/R2_Reasoner .

[Arxiv](https://arxiv.org/abs/2506.05901)