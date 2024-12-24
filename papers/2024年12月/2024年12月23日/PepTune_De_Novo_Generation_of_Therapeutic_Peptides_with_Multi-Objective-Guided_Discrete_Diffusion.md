# PepTune：利用多目标引导的离散扩散实现治疗性肽的从头生成

发布时间：2024年12月23日

`其他` `药物开发`

> PepTune: De Novo Generation of Therapeutic Peptides with Multi-Objective-Guided Discrete Diffusion

# 摘要

> 肽类疗法作为主要的药物类别，在糖尿病、癌症等疾病治疗方面成绩斐然，像GLP-1受体激动剂就为2型糖尿病和肥胖症的治疗带来了变革。然而，设计能同时满足诸如靶标结合亲和力、溶解性、膜通透性等多个相互冲突目标的肽，仍是巨大挑战。传统的药物开发和基于结构的设计对此类任务成效不佳，因其无法优化对治疗效果至关重要的全局功能特性。现有的生成框架大多局限于连续空间、无条件输出或单目标引导，难以胜任跨多个属性的离散序列优化。为此，我们推出了PepTune，这是一个用于同时生成和优化治疗性肽SMILES的多目标离散扩散模型。它构建于掩蔽离散语言模型（MDLM）框架之上，通过状态依赖的掩蔽计划和基于惩罚的目标来确保肽结构的有效性。为引导扩散过程，我们提出了基于蒙特卡罗树搜索（MCTS）的策略，平衡了探索与利用，以迭代优化帕累托最优序列。MCTS将基于分类器的奖励与搜索树扩展相结合，克服了离散空间固有的梯度估计难题和数据稀疏性。借助PepTune，我们生成了针对多种治疗特性（包括靶标结合亲和力、膜通透性、溶解性、溶血和在各种疾病相关靶点上的非污染特性）进行优化的多样化、化学修饰的肽。总之，我们的结果表明，MCTS引导的离散扩散是离散状态空间中多目标序列设计的有力且模块化的方法。

> Peptide therapeutics, a major class of medicines, have achieved remarkable success across diseases such as diabetes and cancer, with landmark examples such as GLP-1 receptor agonists revolutionizing the treatment of type-2 diabetes and obesity. Despite their success, designing peptides that satisfy multiple conflicting objectives, such as target binding affinity, solubility, and membrane permeability, remains a major challenge. Classical drug development and structure-based design are ineffective for such tasks, as they fail to optimize global functional properties critical for therapeutic efficacy. Existing generative frameworks are largely limited to continuous spaces, unconditioned outputs, or single-objective guidance, making them unsuitable for discrete sequence optimization across multiple properties. To address this, we present PepTune, a multi-objective discrete diffusion model for the simultaneous generation and optimization of therapeutic peptide SMILES. Built on the Masked Discrete Language Model (MDLM) framework, PepTune ensures valid peptide structures with state-dependent masking schedules and penalty-based objectives. To guide the diffusion process, we propose a Monte Carlo Tree Search (MCTS)-based strategy that balances exploration and exploitation to iteratively refine Pareto-optimal sequences. MCTS integrates classifier-based rewards with search-tree expansion, overcoming gradient estimation challenges and data sparsity inherent to discrete spaces. Using PepTune, we generate diverse, chemically-modified peptides optimized for multiple therapeutic properties, including target binding affinity, membrane permeability, solubility, hemolysis, and non-fouling characteristics on various disease-relevant targets. In total, our results demonstrate that MCTS-guided discrete diffusion is a powerful and modular approach for multi-objective sequence design in discrete state spaces.

[Arxiv](https://arxiv.org/abs/2412.17780)