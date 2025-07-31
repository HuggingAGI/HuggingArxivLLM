# VL-Cogito：通过渐进式课程强化学习实现高级多模态推理

发布时间：2025年07月30日

`LLM理论`

> VL-Cogito: Progressive Curriculum Reinforcement Learning for Advanced Multimodal Reasoning

# 摘要

> 强化学习在提升大型语言模型推理能力方面已展现出显著效果。近期研究逐步将这一技术拓展至多模态推理领域。然而，多模态任务的复杂性和多样性，尤其是语义内容和问题形式上的差异，导致现有模型在不同领域和难度上表现不一。为解决这一问题，我们提出VL-Cogito，该模型基于创新的多阶段渐进式课程强化学习(PCuRL)框架训练而成。PCuRL通过系统性地引导模型逐步完成难度递增的任务，显著提升其在各种多模态情境下的推理能力。框架的两大创新点包括：(1)在线难度软加权机制，可在连续强化学习训练阶段动态调整难度；(2)动态长度奖励机制，使模型根据任务复杂度自适应调节推理路径长度，实现推理效率与正确性的平衡。实验结果表明，VL-Cogito在数学、科学、逻辑和一般理解等多模态基准测试中表现优异，超越现有推理模型，充分证明了我们方法的有效性。


> Reinforcement learning has proven its effectiveness in enhancing the reasoning capabilities of large language models. Recent research efforts have progressively extended this paradigm to multimodal reasoning tasks. Due to the inherent complexity and diversity of multimodal tasks, especially in semantic content and problem formulations, existing models often exhibit unstable performance across various domains and difficulty levels. To address these limitations, we propose VL-Cogito, an advanced multimodal reasoning model trained via a novel multi-stage Progressive Curriculum Reinforcement Learning (PCuRL) framework. PCuRL systematically guides the model through tasks of gradually increasing difficulty, substantially improving its reasoning abilities across diverse multimodal contexts. The framework introduces two key innovations: (1) an online difficulty soft weighting mechanism, dynamically adjusting training difficulty across successive RL training stages; and (2) a dynamic length reward mechanism, which encourages the model to adaptively regulate its reasoning path length according to task complexity, thus balancing reasoning efficiency with correctness. Experimental evaluations demonstrate that VL-Cogito consistently matches or surpasses existing reasoning-oriented models across mainstream multimodal benchmarks spanning mathematics, science, logic, and general understanding, validating the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2507.22607)