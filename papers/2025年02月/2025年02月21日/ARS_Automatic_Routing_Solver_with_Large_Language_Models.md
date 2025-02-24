# ARS: 基于大型语言模型的自动路由求解器

发布时间：2025年02月21日

`LLM应用` `供应链管理`

> ARS: Automatic Routing Solver with Large Language Models

# 摘要

> 现实世界中的车辆路径问题（VRP）往往伴随着多种实际约束，使得手动设计求解器既耗时又耗力。尽管自动化设计路径算法的研究日益受到关注，但现有研究仅限于探索少量的VRP变体，且未能有效应对现实场景中复杂多样的约束条件。为此，我们提出了RoutBench——一个基于24个属性构建的包含1000种VRP变体的基准测试集，用于评估自动路径求解器在处理复杂约束方面的效果。同时，我们还推出了自动路径求解器（ARS），该方法通过大型语言模型（LLM）代理，基于问题描述和从数据库中选取的代表性约束条件，自动生成感知约束的启发式代码，从而优化基础算法框架。实验结果表明，ARS在所有基准测试中均超越了现有基于LLM的方法和传统求解器，能够自动解决91.67%的常见VRP问题，并在所有基准上实现了至少30%的性能提升。


> Real-world Vehicle Routing Problems (VRPs) are characterized by a variety of practical constraints, making manual solver design both knowledge-intensive and time-consuming. Although there is increasing interest in automating the design of routing algorithms, existing research has explored only a limited array of VRP variants and fails to adequately address the complex and prevalent constraints encountered in real-world situations. To fill this gap, this paper introduces RoutBench, a benchmark of 1,000 VRP variants derived from 24 attributes, for evaluating the effectiveness of automatic routing solvers in addressing complex constraints. Along with RoutBench, we present the Automatic Routing Solver (ARS), which employs Large Language Model (LLM) agents to enhance a backbone algorithm framework by automatically generating constraint-aware heuristic code, based on problem descriptions and several representative constraints selected from a database. Our experiments show that ARS outperforms state-of-the-art LLM-based methods and commonly used solvers, automatically solving 91.67% of common VRPs and achieving at least a 30% improvement across all benchmarks.

[Arxiv](https://arxiv.org/abs/2502.15359)