# # TextAtari：十万帧语言智能体游戏

发布时间：2025年06月04日

`LLM应用` `决策系统`

> TextAtari: 100K Frames Game Playing with Language Agents

# 摘要

> 我们推出TextAtari，一个专为评估语言代理在长跨度决策任务中表现而设计的基准测试，涵盖多达10万步的复杂挑战。通过将经典Atari游戏的视觉状态转化为详尽的文本描述，TextAtari搭建了一个连接顺序决策与自然语言处理的创新测试平台。该基准包含近100个任务，涵盖不同复杂度、动作空间和规划跨度，所有任务均通过无监督表示学习框架（AtariARI）以文本形式呈现。我们对三个开源大型语言模型（Qwen2.5-7B、Gemma-7B 和 Llama3.1-8B）进行了全面评估，分别在零-shot、少-shot链式推理和反思推理三种代理框架下，探究不同先验知识形式对长跨度任务的影响。通过基础、模糊、手动增强和基于参考四种场景，深入分析语义理解、指令理解以及专家演示对代理决策的塑造作用。实验结果表明，在涉及广泛规划的任务中，语言代理与人类玩家之间存在显著性能差距，凸显了在数万步中进行顺序推理、状态跟踪和战略规划的挑战。TextAtari不仅提供标准化的评估协议和基线实现，更为语言模型与规划领域的交叉研究搭建了重要框架，推动相关技术的持续发展。

> We present TextAtari, a benchmark for evaluating language agents on very long-horizon decision-making tasks spanning up to 100,000 steps. By translating the visual state representations of classic Atari games into rich textual descriptions, TextAtari creates a challenging test bed that bridges sequential decision-making with natural language processing. The benchmark includes nearly 100 distinct tasks with varying complexity, action spaces, and planning horizons, all rendered as text through an unsupervised representation learning framework (AtariARI). We evaluate three open-source large language models (Qwen2.5-7B, Gemma-7B, and Llama3.1-8B) across three agent frameworks (zero-shot, few-shot chain-of-thought, and reflection reasoning) to assess how different forms of prior knowledge affect performance on these long-horizon challenges. Four scenarios-Basic, Obscured, Manual Augmentation, and Reference-based-investigate the impact of semantic understanding, instruction comprehension, and expert demonstrations on agent decision-making. Our results reveal significant performance gaps between language agents and human players in extensive planning tasks, highlighting challenges in sequential reasoning, state tracking, and strategic planning across tens of thousands of steps. TextAtari provides standardized evaluation protocols, baseline implementations, and a framework for advancing research at the intersection of language models and planning.

[Arxiv](https://arxiv.org/abs/2506.04098)