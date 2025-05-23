# 现代机器学习在组合优化中的全面求解评估

发布时间：2025年05月22日

`LLM应用

理由：这篇论文讨论了机器学习，包括大型语言模型（LLM）代理在组合优化问题中的应用。它介绍了一个基准测试集FrontierCO，用于评估包括LLM代理在内的各种ML求解器。因此，它属于LLM应用类别。` `运筹学` `组合优化`

> A Comprehensive Evaluation of Contemporary ML-Based Solvers for Combinatorial Optimization

# 摘要

> 机器学习在组合优化问题的模型设计与优化中展现出了巨大潜力。然而，目前的研究大多基于小规模合成数据集，这引发了人们对 ML 求解器在真实大规模 CO 场景中实际效果的担忧。此外，现有 CO 基准测试集常因训练数据不足而限制了对数据驱动方法的评估。为此，我们推出了 FrontierCO，一个涵盖八种典型 CO 问题类型并评估 16 种代表性 ML 求解器（包括图神经网络和 LLM 代理）的全面基准测试集。 FrontierCO 采用了来自工业应用和前沿 CO 研究中的具有挑战性的实例，既保证了现实问题难度，又提供了丰富的训练数据。我们的实证结果揭示了当前 ML 方法的优势与局限，为机器学习与组合优化交叉领域的稳健发展提供了重要指导。数据可在 https://huggingface.co/datasets/CO-Bench/FrontierCO 获取。

> Machine learning (ML) has demonstrated considerable potential in supporting model design and optimization for combinatorial optimization (CO) problems. However, much of the progress to date has been evaluated on small-scale, synthetic datasets, raising concerns about the practical effectiveness of ML-based solvers in real-world, large-scale CO scenarios. Additionally, many existing CO benchmarks lack sufficient training data, limiting their utility for evaluating data-driven approaches. To address these limitations, we introduce FrontierCO, a comprehensive benchmark that covers eight canonical CO problem types and evaluates 16 representative ML-based solvers--including graph neural networks and large language model (LLM) agents. FrontierCO features challenging instances drawn from industrial applications and frontier CO research, offering both realistic problem difficulty and abundant training data. Our empirical results provide critical insights into the strengths and limitations of current ML methods, helping to guide more robust and practically relevant advances at the intersection of machine learning and combinatorial optimization. Our data is available at https://huggingface.co/datasets/CO-Bench/FrontierCO.

[Arxiv](https://arxiv.org/abs/2505.16952)