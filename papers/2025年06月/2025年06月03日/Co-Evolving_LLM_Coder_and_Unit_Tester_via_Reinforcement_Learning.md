# 利用强化学习实现LLM编码器与单元测试器的协同进化

发布时间：2025年06月03日

`LLM应用` `软件工程` `人工智能`

> Co-Evolving LLM Coder and Unit Tester via Reinforcement Learning

# 摘要

> 我们提出了一种名为 CURE 的新型强化学习框架，通过专门设计的奖励机制，能够基于交互结果共同进化代码和单元测试生成能力，无需任何真实代码作为监督。这一方法不仅支持灵活且可扩展的训练，还使单元测试生成器能够直接从编码器的错误中学习。我们基于 Qwen2.5-Instruct 模型优化得到的 ReasonFlux-Coder-7B 和 14B 模型，在代码生成准确性方面提升了 5.3%，在 Best-of-N 准确性方面提升了 9.0%，超越了同规模的 Qwen-Coder、DeepSeek-Coder 和 Seed-Coder。这些模型在测试时间缩放和智能体编码等下游任务中也表现出色，较基线模型提升了 8.1%。对于长链推理模型，我们的 ReasonFlux-Coder-4B 在单元测试生成方面持续优于 Qwen3-4B，同时实现了 64.8% 的推理效率。更值得注意的是，我们发现我们的模型还可以作为强化学习中基线模型的有效奖励模型。项目地址：https://github.com/Gen-Verse/CURE

> We propose CURE, a novel reinforcement learning framework with a dedicated reward design that co-evolves coding and unit test generation capabilities based on their interaction outcomes, without any ground-truth code as supervision. This approach enables flexible and scalable training and allows the unit tester to learn directly from the coder's mistakes. Our derived ReasonFlux-Coder-7B and 14B models improve code generation accuracy by 5.3% and Best-of-N accuracy by 9.0% after optimization on Qwen2.5-Instruct models, outperforming similarly sized Qwen-Coder, DeepSeek-Coder, and Seed-Coder. They naturally extend to downstream tasks such as test-time scaling and agentic coding-achieving a 8.1% improvement over the base model. For the long-CoT model, our ReasonFlux-Coder-4B consistently outperforms Qwen3-4B while achieving 64.8% inference efficiency in unit test generation. Notably, we also find that our model can serve as an effective reward model for reinforcement learning on base models. Project: https://github.com/Gen-Verse/CURE

[Arxiv](https://arxiv.org/abs/2506.03136)