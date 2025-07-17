# 分步策略方法用于罕见工具知识 (SPaRK)：驱动大型语言模型中多样化工具使用的离线强化学习

发布时间：2025年07月15日

`LLM应用` `学术研究`

> Step-wise Policy for Rare-tool Knowledge (SPaRK): Offline RL that Drives Diverse Tool Use in LLMs

# 摘要

> 我们提出了一种名为分步稀有工具知识策略（Step-wise Policy for Rare-tool Knowledge，SPaRK）的新型强化学习框架，该框架能够指导大型语言模型探索超越传统高温采样方法的多样化工具使用模式。基于分步强化学习的最新进展，我们引入了一种双目标奖励系统，同时优化答案质量和工具多样性，并通过在合成生成的MMLU-Pro数据集轨迹上使用离线PPO训练了一个Llama-3.1 8B模型。我们的方法独特地采用了以稀有性优先的开发策略，其中一位GPT-4o评估员对涵盖八种不同工具加上链式思维推理的候选动作进行评分，策略倾向于选择较少使用但仍然可行的工具，以此鼓励系统性探索。实证结果表明，SPaRK在14个MMLU-Pro类别中实现了具有竞争力的性能，同时在工具选择上表现出显著高于基线和监督微调方法的熵值，这表明通过显式工具多样性实现的算法探索能够提升推理能力而不牺牲准确性。

> We present Step-wise Policy for Rare-tool Knowledge (SPaRK), a novel reinforcement learning framework that teaches large language models to explore diverse tool usage patterns beyond conventional high-temperature sampling. Building on recent advances in step-wise reinforcement learning, we introduce a dual-objective reward system that simultaneously optimizes for answer quality and tool diversity, training a Llama-3.1 8B model through offline PPO on synthetically generated trajectories from the MMLU-Pro dataset. Our approach uniquely employs a rarity-first exploitation strategy where a GPT-4o judge scores candidate actions across eight distinct tools plus chain-of-thought reasoning, with the policy favoring less-frequently used but still viable tools to encourage systematic exploration. Empirical results demonstrate that SPaRK achieves competitive performance across 14 MMLU-Pro categories while exhibiting significantly higher entropy in tool selection compared to both baseline and supervised fine-tuning approaches, suggesting that algorithmic exploration through explicit tool diversity can enhance reasoning capabilities without sacrificing accuracy.

[Arxiv](https://arxiv.org/abs/2507.11371)