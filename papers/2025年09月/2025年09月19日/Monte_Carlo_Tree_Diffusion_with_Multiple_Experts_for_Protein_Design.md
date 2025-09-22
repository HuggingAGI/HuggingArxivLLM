# 多专家蒙特卡洛树扩散蛋白质设计

发布时间：2025年09月19日

`其他` `医疗健康`

> Monte Carlo Tree Diffusion with Multiple Experts for Protein Design

# 摘要

> 蛋白质设计旨在生成能折叠成具有特定功能特性结构的氨基酸序列。以往结合自回归语言模型与蒙特卡洛树搜索（MCTS）的方法难以处理长程依赖，且搜索空间过大，实用性受限。为此，我们提出MCTD-ME——多专家蒙特卡洛树扩散（Monte Carlo Tree Diffusion with Multiple Experts），该方法将掩码扩散模型与树搜索相融合，支持多标记规划与高效探索。与自回归规划器不同，MCTD-ME采用生物物理保真度增强的扩散去噪作为展开引擎，可同时修正多个位置，并能扩展至大型序列空间。该方法还借助不同能力的专家增强探索多样性，并通过基于pLDDT的掩码调度进行引导——此调度会针对低置信度区域，同时保留可靠残基。我们还提出了一种新的多专家选择规则（PH-UCT-ME），将预测熵UCT扩展到专家集成场景。在逆折叠任务（CAMEO和PDB基准测试）中，MCTD-ME在序列恢复率（AAR）和结构相似度（scTM）上均超越单专家和无指导基线，且蛋白质越长，性能提升越显著，这得益于多专家的协同指导。更重要的是，该框架具有模型无关性，除逆折叠外，还可应用于从头蛋白质工程、多目标分子生成等多个领域。

> The goal of protein design is to generate amino acid sequences that fold into functional structures with desired properties. Prior methods combining autoregressive language models with Monte Carlo Tree Search (MCTS) struggle with long-range dependencies and suffer from an impractically large search space. We propose MCTD-ME, Monte Carlo Tree Diffusion with Multiple Experts, which integrates masked diffusion models with tree search to enable multi-token planning and efficient exploration. Unlike autoregressive planners, MCTD-ME uses biophysical-fidelity-enhanced diffusion denoising as the rollout engine, jointly revising multiple positions and scaling to large sequence spaces. It further leverages experts of varying capacities to enrich exploration, guided by a pLDDT-based masking schedule that targets low-confidence regions while preserving reliable residues. We propose a novel multi-expert selection rule (PH-UCT-ME) extends predictive-entropy UCT to expert ensembles. On the inverse folding task (CAMEO and PDB benchmarks), MCTD-ME outperforms single-expert and unguided baselines in both sequence recovery (AAR) and structural similarity (scTM), with gains increasing for longer proteins and benefiting from multi-expert guidance. More generally, the framework is model-agnostic and applicable beyond inverse folding, including de novo protein engineering and multi-objective molecular generation.

[Arxiv](https://arxiv.org/abs/2509.15796)