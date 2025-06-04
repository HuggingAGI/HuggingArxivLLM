# AUTOCIRCUIT-RL：基于强化学习的大型语言模型，实现电路拓扑自动化生成

发布时间：2025年06月03日

`LLM应用` `电子设计自动化` `EDA`

> AUTOCIRCUIT-RL: Reinforcement Learning-Driven LLM for Automated Circuit Topology Generation

# 摘要

> 模拟电路拓扑综合是电子设计自动化（EDA）的核心技术，它能够根据设计需求自动化生成电路结构。然而，由于设计空间的复杂性和严格的设计约束，高效实现这一过程面临巨大挑战。我们提出了一种基于强化学习（RL）的全新框架AUTOCIRCUIT-RL，利用大型语言模型（LLMs）的强大能力，实现模拟电路的自动化设计。该框架分为两个阶段：首先通过指令调优让LLM学会根据结构化的设计约束生成电路拓扑，然后通过强化学习进一步优化模型，使其在电路的有效性、效率和输出电压等方面表现更佳。实验结果表明，与现有最佳方法相比，AUTOCIRCUIT-RL生成的有效电路数量提升约12%，设计效率提升约14%，同时将重复设计率降低约38%。即使在数据有限的情况下，它也能成功生成有效电路超过60%，展现出强大的泛化能力。这一成果不仅验证了框架在复杂电路设计中的高效性，也为AI驱动的电路设计开辟了新的可能性，标志着该领域的重要突破。

> Analog circuit topology synthesis is integral to Electronic Design Automation (EDA), enabling the automated creation of circuit structures tailored to specific design requirements. However, the vast design search space and strict constraint adherence make efficient synthesis challenging. Leveraging the versatility of Large Language Models (LLMs), we propose AUTOCIRCUIT-RL,a novel reinforcement learning (RL)-based framework for automated analog circuit synthesis. The framework operates in two phases: instruction tuning, where an LLM learns to generate circuit topologies from structured prompts encoding design constraints, and RL refinement, which further improves the instruction-tuned model using reward models that evaluate validity, efficiency, and output voltage. The refined model is then used directly to generate topologies that satisfy the design constraints. Empirical results show that AUTOCIRCUIT-RL generates ~12% more valid circuits and improves efficiency by ~14% compared to the best baselines, while reducing duplicate generation rates by ~38%. It achieves over 60% success in synthesizing valid circuits with limited training data, demonstrating strong generalization. These findings highlight the framework's effectiveness in scaling to complex circuits while maintaining efficiency and constraint adherence, marking a significant advancement in AI-driven circuit design.

[Arxiv](https://arxiv.org/abs/2506.03122)