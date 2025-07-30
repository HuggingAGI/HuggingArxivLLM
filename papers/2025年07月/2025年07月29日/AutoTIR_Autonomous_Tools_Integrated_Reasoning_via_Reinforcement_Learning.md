# AutoTIR: 通过强化学习实现的自主工具集成推理

发布时间：2025年07月29日

`LLM应用

理由：这篇论文探讨了如何通过强化学习框架改进大型语言模型（LLMs）的工具使用能力，属于LLM的实际应用和增强，因此归类为LLM应用。` `人工智能`

> AutoTIR: Autonomous Tools Integrated Reasoning via Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）通过推理导向的后训练升级为强大的大型推理模型（LRMs）。工具集成推理（TIR）借助外部工具进一步扩展了其能力，但现有方法常依赖僵化的工具使用模式，可能削弱核心语言能力。受人类灵活选择工具的启发，我们推出AutoTIR——一个强化学习框架，让LLMs在推理过程中自主决定是否及如何调用工具，告别死板的工具使用策略。AutoTIR采用混合奖励机制，同时优化任务答案的准确性、结构化输出的规范性，并对错误工具使用加以惩罚，从而推动精准推理与高效工具整合。在知识密集型、数学推理及通用语言建模等多样化任务上的全面评估显示，AutoTIR表现卓越，显著超越基准模型，并在工具使用行为上展现出强大的泛化能力。这证明了强化学习在构建真正通用且可扩展的TIR能力方面的巨大潜力。代码和数据已开源，欢迎访问https://github.com/weiyifan1023/AutoTIR。

> Large Language Models (LLMs), when enhanced through reasoning-oriented post-training, evolve into powerful Large Reasoning Models (LRMs). Tool-Integrated Reasoning (TIR) further extends their capabilities by incorporating external tools, but existing methods often rely on rigid, predefined tool-use patterns that risk degrading core language competence. Inspired by the human ability to adaptively select tools, we introduce AutoTIR, a reinforcement learning framework that enables LLMs to autonomously decide whether and which tool to invoke during the reasoning process, rather than following static tool-use strategies. AutoTIR leverages a hybrid reward mechanism that jointly optimizes for task-specific answer correctness, structured output adherence, and penalization of incorrect tool usage, thereby encouraging both precise reasoning and efficient tool integration. Extensive evaluations across diverse knowledge-intensive, mathematical, and general language modeling tasks demonstrate that AutoTIR achieves superior overall performance, significantly outperforming baselines and exhibits superior generalization in tool-use behavior. These results highlight the promise of reinforcement learning in building truly generalizable and scalable TIR capabilities in LLMs. The code and data are available at https://github.com/weiyifan1023/AutoTIR.

[Arxiv](https://arxiv.org/abs/2507.21836)