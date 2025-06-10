# REMoH：基于大型语言模型的多目标启发式方法的反思性演化

发布时间：2025年06月09日

`LLM应用` `运筹学`

> REMoH: A Reflective Evolution of Multi-objective Heuristics approach via Large Language Models

# 摘要

> 多目标优化在复杂决策任务中扮演着核心角色。传统算法虽有效，但往往需要大量针对具体问题的建模工作，并且难以应对非线性结构。近期，大型语言模型（LLMs）的进步带来了更高的可解释性、适应性和推理能力。本研究提出了一种名为多目标启发式反射进化（REMoH）的创新框架，将NSGA-II与基于LLM的启发式生成相结合。其核心创新点在于引入了反射机制，通过聚类和搜索空间反射，有效指导生成多样化、高质量的启发式方法，从而提升收敛性并保持解的多样性。该方法在 Flexible Job Shop Scheduling Problem (FJSSP) 上进行了深入评估，采用 Dauzere、Barnes 和 Brandimarte 三个实例数据集，与现有最先进的方法进行了全面对比。实验结果表明，REMoH 在减少建模工作量的同时，相较于现有先进方法实现了具有竞争力的结果，并且展现了更强的适应性。这些发现凸显了 LLMs 在增强传统优化方面的潜力，为多目标场景提供了更高的灵活性、可解释性和鲁棒性。

> Multi-objective optimization is fundamental in complex decision-making tasks. Traditional algorithms, while effective, often demand extensive problem-specific modeling and struggle to adapt to nonlinear structures. Recent advances in Large Language Models (LLMs) offer enhanced explainability, adaptability, and reasoning. This work proposes Reflective Evolution of Multi-objective Heuristics (REMoH), a novel framework integrating NSGA-II with LLM-based heuristic generation. A key innovation is a reflection mechanism that uses clustering and search-space reflection to guide the creation of diverse, high-quality heuristics, improving convergence and maintaining solution diversity. The approach is evaluated on the Flexible Job Shop Scheduling Problem (FJSSP) in-depth benchmarking against state-of-the-art methods using three instance datasets: Dauzere, Barnes, and Brandimarte. Results demonstrate that REMoH achieves competitive results compared to state-of-the-art approaches with reduced modeling effort and enhanced adaptability. These findings underscore the potential of LLMs to augment traditional optimization, offering greater flexibility, interpretability, and robustness in multi-objective scenarios.

[Arxiv](https://arxiv.org/abs/2506.07759)