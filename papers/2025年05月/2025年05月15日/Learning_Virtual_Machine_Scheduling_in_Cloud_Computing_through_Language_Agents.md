# 借助语言代理学习云计算中的虚拟机调度

发布时间：2025年05月15日

`Agent` `云计算` `资源调度`

> Learning Virtual Machine Scheduling in Cloud Computing through Language Agents

# 摘要

> 在云服务中，虚拟机（VM）调度是一个典型的在线动态多维装箱问题（ODMBP），具有规模复杂和需求波动大的特点。传统优化方法难以适应实时变化，专家设计的启发式方法策略 rigid，而现有学习方法缺乏泛化和可解释性。为此，本文提出名为 MiCo 的分层语言代理框架，为解决 ODMBP 提供了基于大语言模型（LLM）的启发式设计范式。具体而言，我们将 ODMBP 建模为带有选项的半马尔可夫决策过程（SMDP-Option），通过 Option Miner 和 Option Composer 的两阶段架构实现动态调度。Option Miner 利用 LLM 与构建环境交互，发现多样且有用的非上下文感知策略。Option Composer 则利用 LLM 发现一种组合策略，整合非上下文与上下文策略。在真实企业数据集上的大量实验表明，MiCo 在涉及超过 10,000 台虚拟机的大规模场景中实现了 96.9% 的竞争比。即使面对非平稳请求流和多样化配置，MiCo 仍保持高性能，验证了其在复杂大规模云环境中的有效性。

> In cloud services, virtual machine (VM) scheduling is a typical Online Dynamic Multidimensional Bin Packing (ODMBP) problem, characterized by large-scale complexity and fluctuating demands. Traditional optimization methods struggle to adapt to real-time changes, domain-expert-designed heuristic approaches suffer from rigid strategies, and existing learning-based methods often lack generalizability and interpretability. To address these limitations, this paper proposes a hierarchical language agent framework named MiCo, which provides a large language model (LLM)-driven heuristic design paradigm for solving ODMBP. Specifically, ODMBP is formulated as a Semi-Markov Decision Process with Options (SMDP-Option), enabling dynamic scheduling through a two-stage architecture, i.e., Option Miner and Option Composer. Option Miner utilizes LLMs to discover diverse and useful non-context-aware strategies by interacting with constructed environments. Option Composer employs LLMs to discover a composing strategy that integrates the non-context-aware strategies with the contextual ones. Extensive experiments on real-world enterprise datasets demonstrate that MiCo achieves a 96.9\% competitive ratio in large-scale scenarios involving more than 10,000 virtual machines. It maintains high performance even under nonstationary request flows and diverse configurations, thus validating its effectiveness in complex and large-scale cloud environments.

[Arxiv](https://arxiv.org/abs/2505.10117)