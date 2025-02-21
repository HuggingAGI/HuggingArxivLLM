# # **Logic-RL：用规则强化学习释放LLM推理潜力**

发布时间：2025年02月20日

`LLM应用`

> Logic-RL: Unleashing LLM Reasoning with Rule-Based Reinforcement Learning

# 摘要

> 受 DeepSeek-R1 成功的启发，我们探索了基于规则的强化学习 (RL) 在大型推理模型中的潜力。为了分析推理动态，我们使用合成逻辑谜题作为训练数据，因为它们具有可控的复杂度和直接的答案验证。我们在关键技术上取得了突破，从而实现了有效且稳定的 RL 训练：一个强调思考和回答过程的系统提示，一个严格的格式奖励函数，它会因输出走捷径而进行惩罚，以及一个简单的训练配方，能够实现稳定的收敛。我们的 7B 模型发展出了高级推理技能——例如反思、验证和总结——这些技能在逻辑语料库中是缺失的。令人瞩目的是，仅经过 5K 逻辑问题的训练，它就展现出了对具有挑战性的数学基准测试 AIME 和 AMC 的泛化能力。

> Inspired by the success of DeepSeek-R1, we explore the potential of rule-based reinforcement learning (RL) in large reasoning models. To analyze reasoning dynamics, we use synthetic logic puzzles as training data due to their controllable complexity and straightforward answer verification. We make some key technical contributions that lead to effective and stable RL training: a system prompt that emphasizes the thinking and answering process, a stringent format reward function that penalizes outputs for taking shortcuts, and a straightforward training recipe that achieves stable convergence. Our 7B model develops advanced reasoning skills-such as reflection, verification, and summarization-that are absent from the logic corpus. Remarkably, after training on just 5K logic problems, it demonstrates generalization abilities to the challenging math benchmarks AIME and AMC.

[Arxiv](https://arxiv.org/abs/2502.14768)