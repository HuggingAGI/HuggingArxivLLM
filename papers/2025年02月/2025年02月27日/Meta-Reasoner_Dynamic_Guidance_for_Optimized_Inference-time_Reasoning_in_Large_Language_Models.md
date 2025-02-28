# 元推理器：大型语言模型中推理阶段的优化推理动态引导机制

发布时间：2025年02月27日

`LLM理论` `推理优化` `人工智能`

> Meta-Reasoner: Dynamic Guidance for Optimized Inference-time Reasoning in Large Language Models

# 摘要

> 大型语言模型 (LLMs) 在解决复杂任务时越来越依赖于更长的推理链。然而，这种试错方法常常导致高计算开销和错误传播，早期的错误可能会影响后续步骤。为了解决这些问题，我们引入了Meta-Reasoner框架，该框架通过使LLMs能够“思考如何思考”来动态优化推理过程。受人类元认知和双过程理论的启发，Meta-Reasoner充当一个战略顾问，将高层次的指导与逐步生成分离。它利用“上下文多臂老虎机”来迭代评估推理进展，并选择最优策略（例如回溯、澄清模糊性、从头开始或提出替代方法），并将计算资源重新分配到最有前途的路径。我们在数学推理和谜题上的评估突出了动态推理链在克服LLM推理过程中的固有挑战的潜力，同时也展示了在更广泛的应用中取得成功的前景，为推理密集型任务提供了一个可扩展且灵活的解决方案。


> Large Language Models (LLMs) increasingly rely on prolonged reasoning chains to solve complex tasks. However, this trial-and-error approach often leads to high computational overhead and error propagation, where early mistakes can derail subsequent steps. To address these issues, we introduce Meta-Reasoner, a framework that dynamically optimizes inference-time reasoning by enabling LLMs to "think about how to think." Drawing inspiration from human meta-cognition and dual-process theory, Meta-Reasoner operates as a strategic advisor, decoupling high-level guidance from step-by-step generation. It employs "contextual multi-armed bandits" to iteratively evaluate reasoning progress, and select optimal strategies (e.g., backtrack, clarify ambiguity, restart from scratch, or propose alternative approaches), and reallocates computational resources toward the most promising paths. Our evaluations on mathematical reasoning and puzzles highlight the potential of dynamic reasoning chains to overcome inherent challenges in the LLM reasoning process and also show promise in broader applications, offering a scalable and adaptable solution for reasoning-intensive tasks.

[Arxiv](https://arxiv.org/abs/2502.19918)