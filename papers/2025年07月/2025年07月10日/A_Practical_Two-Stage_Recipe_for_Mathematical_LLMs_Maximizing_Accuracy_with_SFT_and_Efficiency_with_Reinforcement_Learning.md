# 实用两阶段方案打造数学LLM：SFT训练提升准确率，强化学习优化效率

发布时间：2025年07月10日

`LLM理论` `数学推理`

> A Practical Two-Stage Recipe for Mathematical LLMs: Maximizing Accuracy with SFT and Efficiency with Reinforcement Learning

# 摘要

> 提升大型语言模型（LLMs）的数学推理能力是推动AI技术发展的关键挑战。尽管监督微调（SFT）和强化学习（RL）是主流的训练范式，但如何系统地结合这两种方法以同时最大化准确性和效率仍是一个未被充分探索的领域。本文提出了一种实用且有效的训练方案，巧妙地将扩展的SFT与基于在线推理的强化学习（GRPO）相结合。我们主张，这些方法并非相互竞争，而是相辅相成：首先通过延长SFT阶段将模型的准确性推向极限，随后通过GRPO阶段在保持峰值性能的同时显著提升代币效率。实验表明，将SFT扩展到多达10个周期对于实现性能突破至关重要，而GRPO在这一框架中的主要作用是优化解决方案长度。我们的方案通过在具有挑战性的基准测试中的顶级性能表现得到了严格验证，包括在严格无泄漏的AI数学奥林匹克竞赛（AIMO）中超过2200支团队的高排名。这项研究为社区提供了一个经过实战验证的蓝图，用于开发既高度准确又实际高效的最新数学推理器。为了确保完全可重复性和支持未来研究，我们将整个框架开源，包括所有代码、模型检查点和训练配置，地址为https://github.com/analokmaus/kaggle-aimo2-fast-math-r1.

> Enhancing the mathematical reasoning of Large Language Models (LLMs) is a pivotal challenge in advancing AI capabilities. While Supervised Fine-Tuning (SFT) and Reinforcement Learning (RL) are the dominant training paradigms, a systematic methodology for combining them to maximize both accuracy and efficiency remains largely unexplored. This paper introduces a practical and effective training recipe that strategically integrates extended SFT with RL from online inference (GRPO). We posit that these methods play complementary, not competing, roles: a prolonged SFT phase first pushes the model's accuracy to its limits, after which a GRPO phase dramatically improves token efficiency while preserving this peak performance. Our experiments reveal that extending SFT for as many as 10 epochs is crucial for performance breakthroughs, and that the primary role of GRPO in this framework is to optimize solution length. The efficacy of our recipe is rigorously validated through top-tier performance on challenging benchmarks, including a high rank among over 2,200 teams in the strictly leak-free AI Mathematical Olympiad (AIMO). This work provides the community with a battle-tested blueprint for developing state-of-the-art mathematical reasoners that are both exceptionally accurate and practically efficient. To ensure full reproducibility and empower future research, we will open-source our entire framework, including all code, model checkpoints, and training configurations at https://github.com/analokmaus/kaggle-aimo2-fast-math-r1.

[Arxiv](https://arxiv.org/abs/2507.08267)