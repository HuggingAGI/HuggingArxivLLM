# # ReTool：基于强化学习的大型语言模型工具战略性使用

发布时间：2025年04月15日

`LLM应用` `数学竞赛` `数学推理`

> ReTool: Reinforcement Learning for Strategic Tool Use in LLMs

# 摘要

> 尽管使用强化学习（RL）训练的推理模型（如DeepSeek R1）在文本推理方面表现出色，但在几何推理、简洁计算或复杂方程求解等需要结构化问题解决的场景中，它们的表现并不理想。这些领域正是代码解释器（CI）等计算工具大显身手的地方。为了解决这一问题，我们提出了ReTool，通过工具集成学习来增强长文本推理能力，主要包含两大创新点：一是将实时代码执行无缝融入自然语言推理过程；二是采用自动化RL范式，支持多轮实时代码执行的策略展开，并通过结果反馈教导模型何时以及如何调用工具。ReTool采用系统化的训练框架，首先通过生成合成冷启动数据，创建代码增强的长文本推理轨迹，用于微调基础模型。随后，通过将任务结果作为奖励信号进行RL训练，迭代优化模型的工具使用策略，使其能够在无需人工干预的情况下自主发现最优工具调用模式。在具有挑战性的数学竞赛基准AIME上的实验结果令人瞩目：我们的32B模型仅需400步训练即可达到67%的准确率，相较于基于文本的RL基线（40%准确率，1080步训练），在效率和性能上均有显著提升。更令人欣喜的是，在扩展设置下，ReTool-32B的准确率达到了72.5%，远超OpenAI的o1-preview 27.9%。进一步分析发现，模型不仅能够自主纠错代码，还展现出“顿悟时刻”，标志着其在自适应工具使用方面已达到新的高度。这些发现不仅凸显了基于结果驱动的工具集成在推进复杂数学推理方面的巨大潜力，更为神经符号混合系统的未来发展提供了重要启示。

> While reasoning models (e.g., DeepSeek R1) trained with reinforcement learning (RL), excel in textual reasoning, they struggle in scenarios requiring structured problem-solving, such as geometric reasoning, concise computation, or complex equation solving-areas where computational tools like code interpreters (CI) demonstrate distinct advantages. To bridge this gap, we propose ReTool, which enhances long-form reasoning with tool-integrated learning, including two key features: (1) dynamic interleaving of real-time code execution within natural language reasoning processes, and (2) an automated RL paradigm that allows policy rollouts with multi-turn real-time code execution and teaches the model in learning when and how to invoke tools based on outcome feedback. ReTool employs a systematic training framework, beginning with synthetic cold-start data generation to produce code-augmented long-form reasoning traces for fine-tuning base models. Subsequent RL training leverages task outcomes as rewards to iteratively refine the model's tool use strategy, enabling autonomous discovery of optimal tool invocation patterns without human priors. Experiments on the challenging MATH Olympiad benchmark AIME demonstrate ReTool's superiority: Our 32B model achieves 67% accuracy with 400 training steps, outperforming text-based RL baseline (40% accuracy, 1080 steps) in efficiency and performance. Remarkably, ReTool-32B attains 72.5% accuracy in extended settings, surpassing OpenAI's o1-preview by 27.9%. Further analysis reveals emergent behaviors such as code self-correction, signaling an ''aha moment'' in which the model autonomously masters adaptive tool use. These findings highlight the promise of outcome-driven tool integration for advancing complex mathematical reasoning and offer new insights into hybrid neuro-symbolic systems.

[Arxiv](https://arxiv.org/abs/2504.11536)