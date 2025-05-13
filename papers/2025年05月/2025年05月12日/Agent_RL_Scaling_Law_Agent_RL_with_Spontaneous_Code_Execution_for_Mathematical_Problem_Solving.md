# 智能体强化学习的缩放定律：支持自发代码执行的数学问题求解方法。

发布时间：2025年05月12日

`Agent` `数学推理`

> Agent RL Scaling Law: Agent RL with Spontaneous Code Execution for Mathematical Problem Solving

# 摘要

> 大型语言模型（LLMs）在需要精确计算的数学推理任务中常常表现欠佳。虽然基于结果奖励的强化学习（RL）能够提升文本推理能力，但智能体如何自主学习利用外部工具（如代码执行）仍是一个关键问题。我们提出了ZeroTIR方法，通过训练基础LLMs自发生成并执行Python代码来解决数学问题，且无需监督式工具使用示例。我们的研究发现，随着RL训练的推进，关键指标能够可预测地增长。具体而言，训练步骤的增加显著提升了自发代码执行频率、平均响应长度，以及最终任务准确性。这表明计算训练投入与有效工具增强推理策略的出现之间存在可量化的关联。我们实现了一个包含解耦代码执行环境的稳健框架，并在标准RL算法和框架上验证了我们的发现。实验表明，ZeroTIR在具有挑战性的数学基准测试中显著超越了无工具的ZeroRL基线。我们的研究为智能体强化学习中自主工具使用能力的获取和扩展提供了基础理解，并为未来研究提供了可复现的基准。代码已发布于\href{https://github.com/Anonymize-Author/AgentRL}{https://github.com/Anonymize-Author/AgentRL}。

> Large Language Models (LLMs) often struggle with mathematical reasoning tasks requiring precise, verifiable computation. While Reinforcement Learning (RL) from outcome-based rewards enhances text-based reasoning, understanding how agents autonomously learn to leverage external tools like code execution remains crucial. We investigate RL from outcome-based rewards for Tool-Integrated Reasoning, ZeroTIR, training base LLMs to spontaneously generate and execute Python code for mathematical problems without supervised tool-use examples. Our central contribution is we demonstrate that as RL training progresses, key metrics scale predictably. Specifically, we observe strong positive correlations where increased training steps lead to increases in the spontaneous code execution frequency, the average response length, and, critically, the final task accuracy. This suggests a quantifiable relationship between computational effort invested in training and the emergence of effective, tool-augmented reasoning strategies. We implement a robust framework featuring a decoupled code execution environment and validate our findings across standard RL algorithms and frameworks. Experiments show ZeroTIR significantly surpasses non-tool ZeroRL baselines on challenging math benchmarks. Our findings provide a foundational understanding of how autonomous tool use is acquired and scales within Agent RL, offering a reproducible benchmark for future studies. Code is released at \href{https://github.com/Anonymize-Author/AgentRL}{https://github.com/Anonymize-Author/AgentRL}.

[Arxiv](https://arxiv.org/abs/2505.07773)