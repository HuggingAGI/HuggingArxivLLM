# TableMind：面向工具增强表格推理的自主程序化智能体

发布时间：2025年09月07日

`Agent` `金融科技`

> TableMind: An Autonomous Programmatic Agent for Tool-Augmented Table Reasoning

# 摘要

> 表格推理在金融、医疗、科研等领域的结构化数据应用中至关重要。大型语言模型（LLMs）虽在多步推理中展现潜力，但纯文本方法在处理该任务所需的复杂数值计算和细粒度操作时常常捉襟见肘。工具集成推理通过显式代码执行提升了计算准确性，然而现有系统多依赖僵化模式与监督模仿，缺乏真正的自主适应能力。为此，我们提出TableMind——一个LLM驱动的表格推理智能体，它具备三大核心能力：（i）自主执行多轮工具调用；（ii）在安全沙箱环境中编写并执行数据分析代码，实现数据分析与精确数值推理；（iii）展现规划与自我反思等高阶能力，能够动态调整策略。为实现这些能力，我们在高性能预训练语言模型基础上构建了两阶段微调范式：首先在高质量推理轨迹上进行监督微调，以建立有效的工具使用模式；随后通过强化微调优化多目标策略。特别地，我们提出排序感知策略优化（RAPO）——当高质量轨迹的输出概率低于低质量轨迹时，该方法会增加高质量轨迹的更新权重，从而更稳定地引导模型生成更优、更准确的答案。在多个主流基准数据集上的大量实验表明，TableMind的性能显著优于现有竞争基线，在推理准确性和计算精度上均实现了大幅提升。

> Table reasoning is crucial for leveraging structured data in domains such as finance, healthcare, and scientific research. While large language models (LLMs) show promise in multi-step reasoning, purely text-based methods often struggle with the complex numerical computations and fine-grained operations inherently required in this task. Tool-integrated reasoning improves computational accuracy via explicit code execution, yet existing systems frequently rely on rigid patterns, supervised imitation, and lack true autonomous adaptability. In this paper, we present TableMind, an LLM-driven table reasoning agent that (i) autonomously performs multi-turn tool invocation, (ii) writes and executes data-analyzing code in a secure sandbox environment for data analysis and precise numerical reasoning, and (iii) exhibits high-level capabilities such as planning and self-reflection to adapt strategies. To realize these capabilities, we adopt a two-stage fine-tuning paradigm built on top of a powerful pre-trained language model: supervised fine-tuning on high-quality reasoning trajectories to establish effective tool usage patterns, followed by reinforcement fine-tuning to optimize multi-objective strategies. In particular, we propose Rank-Aware Policy Optimization (RAPO), which increases the update weight of high-quality trajectories when their output probabilities are lower than those of low-quality ones, thereby guiding the model more consistently toward better and more accurate answers. Extensive experiments on several mainstream benchmarks demonstrate that TableMind achieves superior performance compared to competitive baselines, yielding substantial gains in both reasoning accuracy and computational precision.

[Arxiv](https://arxiv.org/abs/2509.06278)