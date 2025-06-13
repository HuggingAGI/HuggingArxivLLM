# BugGen：自修正多智能体LLM管线，实现真实RTL缺陷合成。

发布时间：2025年06月12日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）来生成和验证硬件设计中的功能缺陷，从而提高调试效率。虽然提到了多智能体管道，但核心是LLMs的应用，属于LLM应用类别。` `电子设计自动化` `硬件验证`

> BugGen: A Self-Correcting Multi-Agent LLM Pipeline for Realistic RTL Bug Synthesis

# 摘要

> 硬件复杂性持续加剧对验证资源的压力，推动了机器学习（ML）方法在提升调试效率中的应用。然而，ML辅助调试严重依赖于多样且可扩展的缺陷数据集，而现有手动或自动化缺陷注入方法无法可靠生成此类数据集。我们推出了BugGen，首个完全自主的多智能体管道，利用大型语言模型（LLMs）系统性地在RTL中生成、插入和验证现实的功能缺陷。

BugGen通过模块划分、闭环智能架构选择变异目标、迭代优化和回滚机制，确保了语法正确性和功能可检测性。在OpenTitan的五个IP模块上进行评估，BugGen生成了500个独特缺陷，功能准确率达到94%，实现了每小时验证17.7个缺陷的吞吐量——比典型的手动专家注入快五倍以上。

此外，BugGen在OpenTitan回归测试中发现了104个先前未检测到的缺陷，凸显了其在揭示验证覆盖率缺口方面的实用性。与Certitude相比，BugGen在语法准确性上高出一倍以上，更深入地揭示了测试平台的盲点，并生成了更具功能意义和复杂性的缺陷场景。

更重要的是，当使用这些BugGen生成的数据集训练ML故障分类模型时，我们在不同IP模块上实现了高达88.1%-93.2%的高分类准确率，验证了生成缺陷的实际效用和现实性。BugGen因此提供了一个可扩展的解决方案，用于生成高质量的缺陷数据集，显著提升了验证效率和ML辅助调试能力。

> Hardware complexity continues to strain verification resources, motivating the adoption of machine learning (ML) methods to improve debug efficiency. However, ML-assisted debugging critically depends on diverse and scalable bug datasets, which existing manual or automated bug insertion methods fail to reliably produce. We introduce BugGen, a first of its kind, fully autonomous, multi-agent pipeline leveraging Large Language Models (LLMs) to systematically generate, insert, and validate realistic functional bugs in RTL. BugGen partitions modules, selects mutation targets via a closed-loop agentic architecture, and employs iterative refinement and rollback mechanisms to ensure syntactic correctness and functional detectability. Evaluated across five OpenTitan IP blocks, BugGen produced 500 unique bugs with 94% functional accuracy and achieved a throughput of 17.7 validated bugs per hour-over five times faster than typical manual expert insertion. Additionally, BugGen identified 104 previously undetected bugs in OpenTitan regressions, highlighting its utility in exposing verification coverage gaps. Compared against Certitude, BugGen demonstrated over twice the syntactic accuracy, deeper exposure of testbench blind spots, and more functionally meaningful and complex bug scenarios. Furthermore, when these BugGen-generated datasets were employed to train ML-based failure triage models, we achieved high classification accuracy (88.1%-93.2%) across different IP blocks, confirming the practical utility and realism of generated bugs. BugGen thus provides a scalable solution for generating high-quality bug datasets, significantly enhancing verification efficiency and ML-assisted debugging.

[Arxiv](https://arxiv.org/abs/2506.10501)