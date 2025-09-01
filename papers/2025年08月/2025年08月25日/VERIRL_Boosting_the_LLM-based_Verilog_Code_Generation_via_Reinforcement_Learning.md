# VERIRL：借助强化学习增强基于LLM的Verilog代码生成

发布时间：2025年08月25日

`强化学习` `工业与制造`

> VERIRL: Boosting the LLM-based Verilog Code Generation via Reinforcement Learning

# 摘要

> 代码生成领域近年来在软件各领域取得显著突破，但硬件描述语言（如Verilog）因其并发语义复杂、语法规则严格且仿真难度大，相关研究仍较为匮乏。为此，我们提出了一种专为Verilog代码生成设计的强化学习（RL）框架VERIRL，以应对上述挑战。我们首先构建了高质量数据集Veribench-53K——该数据集从70多万个Verilog问题中精心筛选而来，并辅以结构化提示、复杂度标签及多样化测试平台。针对奖励信号稀疏且噪声大的问题，我们提出基于回溯的重评分机制，通过推理路径与迭代优化提升反馈可靠性，进而支持奖励模型训练。此外，为缓解RL微调过程中的灾难性遗忘与过拟合，我们设计了样本平衡加权策略，可基于奖励概率分布自适应平衡学习动态。这些创新被整合到一个迭代RL框架中，实现策略模型与奖励模型的协同优化。相比依赖大规模闭源模型蒸馏的CraftRTL，以及难以处理稀疏反馈的DeepSeek类方法，我们的方法仅使用更小但高质量的数据集结合RL优化，便实现了更优性能。在Verilog生成任务上的实验表明，该方法性能达到当前最优，在测试通过率、功能正确性及编译鲁棒性方面均有显著提升。研究结果表明，强化学习驱动的方法在硬件领域结构化代码生成中具有巨大潜力。VERIRL已开源，项目地址：https://github.com/omniAI-Lab/VeriRL。

> Recent advancements in code generation have shown remarkable success across software domains, yet hardware description languages (HDLs) such as Verilog remain underexplored due to their concurrency semantics, syntactic rigidity, and simulation complexity. In this work, we address these challenges by introducing a reinforcement learning (RL) framework tailored for Verilog code generation. We first construct Veribench-53K, a high-quality dataset curated from over 700K Verilog problems, enriched with structured prompts, complexity labels, and diverse testbenches. To tackle the problem of sparse and noisy reward signals, we propose a Trace-back based Rescore mechanism that leverages reasoning paths and iterative refinement to enhance feedback reliability and support reward model training. Furthermore, to mitigate catastrophic forgetting and overfitting during RL fine-tuning, we introduce a sample-balanced weighting strategy that adaptively balances learning dynamics based on reward-probability distributions. These innovations are integrated into an iterative RL pipeline that co-evolves the policy and reward models. In contrast to recent work such as CraftRTL, which relies on large-scale closed-source model distillation, and DeepSeek-style approaches that struggle with sparse feedback, our method demonstrates superior performance using a smaller but high-quality dataset combined with RL optimization. Experiments on Verilog generation tasks demonstrate state-of-the-art performance, with substantial gains in test pass rate, functional correctness, and compilation robustness. Our findings highlight the potential of RL-driven approaches for structured code generation in hardware-centric domains. VERIRL is publicly available at https://github.com/omniAI-Lab/VeriRL.

[Arxiv](https://arxiv.org/abs/2508.18462)