# 激励双过程思维，提升大型语言模型推理效率

发布时间：2025年05月22日

`LLM理论` `人工智能` `机器学习`

> Incentivizing Dual Process Thinking for Efficient Large Language Model Reasoning

# 摘要

> 大型推理模型（LRMs）在复杂推理任务中展现出了强大的推理能力，但同时也面临着过度思考的挑战，无论任务难度如何，都会产生冗余内容。受认知科学中的双过程理论启发，我们提出了自适应认知策略优化（ACPO），这是一种强化学习框架，通过自适应认知资源分配和动态系统切换，帮助LRMs实现更高效的推理。ACPO的核心在于两个关键创新：首先，引入系统感知推理令牌，显式地表示不同的思考模式，使模型的认知过程更加透明；其次，结合在线难度估计和令牌长度预算，为强化学习过程中的自适应系统切换和推理提供指导。为此，我们设计了一种两阶段的训练策略。第一阶段通过监督微调启动模型，使其能够生成具有明确思考模式的推理路径。第二阶段则应用ACPO，进一步优化模型的自适应系统切换能力，以实现更精准的难度感知推理。实验结果表明，ACPO不仅有效减少了冗余推理，还能够根据任务复杂性自适应地调整认知资源分配，从而实现高效的混合推理。

> Large reasoning models (LRMs) have demonstrated strong performance on complex reasoning tasks, but often suffer from overthinking, generating redundant content regardless of task difficulty. Inspired by the dual process theory in cognitive science, we propose Adaptive Cognition Policy Optimization (ACPO), a reinforcement learning framework that enables LRMs to achieve efficient reasoning through adaptive cognitive allocation and dynamic system switch. ACPO incorporates two key components: (1) introducing system-aware reasoning tokens to explicitly represent the thinking modes thereby making the model's cognitive process transparent, and (2) integrating online difficulty estimation and token length budget to guide adaptive system switch and reasoning during reinforcement learning. To this end, we propose a two-stage training strategy. The first stage begins with supervised fine-tuning to cold start the model, enabling it to generate reasoning paths with explicit thinking modes. In the second stage, we apply ACPO to further enhance adaptive system switch for difficulty-aware reasoning. Experimental results demonstrate that ACPO effectively reduces redundant reasoning while adaptively adjusting cognitive allocation based on task complexity, achieving efficient hybrid reasoning.

[Arxiv](https://arxiv.org/abs/2505.16315)