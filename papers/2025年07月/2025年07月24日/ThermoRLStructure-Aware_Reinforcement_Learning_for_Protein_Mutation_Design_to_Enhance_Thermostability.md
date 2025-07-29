# ThermoRL：结构感知强化学习助力蛋白质突变设计，提升热稳定性

发布时间：2025年07月24日

`其他` `生物科学` `蛋白质工程`

> ThermoRL:Structure-Aware Reinforcement Learning for Protein Mutation Design to Enhance Thermostability

# 摘要

> 设计突变以优化蛋白质热稳定性仍具挑战性，这源于序列变异、结构动力学与热稳定性间的复杂关联，通常通过ΔΔG（变性自由能变化）来评估。现有方法多依赖实验随机诱变或基于预定义数据集的预测模型，采用基于序列的启发式方法，并将酶设计视为无需迭代优化的一次性过程。这不仅限制了设计空间的探索，也阻碍了新变异的发现。我们提出ThermoRL，一个基于强化学习（RL）的框架，结合图神经网络（GNN）设计增强热稳定性的突变。该框架整合了预训练的GNN编码器与分层Q-学习网络，并采用代理模型进行奖励反馈，指导RL代理在何处（位置）及如何（突变氨基酸）进行突变以增强热稳定性。实验结果表明，ThermoRL在保持计算效率的同时，展现出优于或与基线方法相当的性能。它能有效筛选出不稳定的突变，并识别出与实验数据一致的稳定突变。此外，ThermoRL能够准确检测未见蛋白质中的关键突变位点，凸显其强大的泛化能力。这一由GNN嵌入驱动的强化学习方法为传统的蛋白质突变设计提供了强大的替代方案。


> Designing mutations to optimize protein thermostability remains challenging due to the complex relationship between sequence variations, structural dynamics, and thermostability, often assessed by δδG
  (the change in free energy of unfolding). Existing methods rely on experimental random mutagenesis or prediction models tested with pre-defined datasets, using sequence-based heuristics and treating enzyme design as a one-step process without iterative refinement, which limits design space exploration and restricts discoveries beyond known variations. We present ThermoRL, a framework based on reinforcement learning (RL) that leverages graph neural networks (GNN) to design mutations with enhanced thermostability. It combines a pre-trained GNN-based encoder with a hierarchical Q-learning network and employs a surrogate model for reward feedback, guiding the RL agent on where (the position) and which (mutant amino acid) to apply for enhanced thermostability. Experimental results show that ThermoRL achieves higher or comparable rewards than baselines while maintaining computational efficiency. It filters out destabilizing mutations and identifies stabilizing mutations aligned with experimental data. Moreover, ThermoRL accurately detects key mutation sites in unseen proteins, highlighting its strong generalizability. This RL-guided approach powered by GNN embeddings offers a robust alternative to traditional protein mutation design.

[Arxiv](https://arxiv.org/abs/2507.18816)