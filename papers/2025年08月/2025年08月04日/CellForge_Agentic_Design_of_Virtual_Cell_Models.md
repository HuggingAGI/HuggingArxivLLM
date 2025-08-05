# CellForge：虚拟细胞模型的智能设计

发布时间：2025年08月04日

`Agent` `生物学`

> CellForge: Agentic Design of Virtual Cell Models

# 摘要

> 虚拟细胞建模是人工智能与生物学交叉领域的一片新兴前沿，致力于定量预测细胞对各种扰动的响应等指标。然而，由于生物系统的复杂性、数据模态的异质性以及跨学科专业知识的需求，自主构建虚拟细胞的计算模型颇具挑战性。在这里，我们介绍了CellForge，一个基于多智能体框架的智能系统，能够将提供的生物数据集和研究目标直接转化为优化的虚拟细胞计算模型。更具体地说，只需输入原始单细胞多组学数据和任务描述，CellForge即可输出优化的模型架构以及用于训练虚拟细胞模型和推理的可执行代码。该框架整合了三个核心模块：任务分析模块用于表征数据集和检索相关文献，方法设计模块中专门的智能体协作开发优化建模策略，以及实验执行模块用于自动化生成代码。设计模块中的智能体分为具有不同视角的专家和一个中央协调员，需要协作交换解决方案直到达成合理共识。我们通过使用涵盖基因敲除、药物处理和细胞因子刺激的六种多样化多模态数据集，展示了CellForge在单细胞扰动预测方面的能力。CellForge始终优于特定任务的最先进方法。总体而言，CellForge展示了具有不同视角的LLM智能体之间的迭代交互如何比直接应对建模挑战提供更好的解决方案。我们的代码公开可用：https://github.com/gersteinlab/CellForge。

> Virtual cell modeling represents an emerging frontier at the intersection of artificial intelligence and biology, aiming to predict quantities such as responses to diverse perturbations quantitatively. However, autonomously building computational models for virtual cells is challenging due to the complexity of biological systems, the heterogeneity of data modalities, and the need for domain-specific expertise across multiple disciplines. Here, we introduce CellForge, an agentic system that leverages a multi-agent framework that transforms presented biological datasets and research objectives directly into optimized computational models for virtual cells. More specifically, given only raw single-cell multi-omics data and task descriptions as input, CellForge outputs both an optimized model architecture and executable code for training virtual cell models and inference. The framework integrates three core modules: Task Analysis for presented dataset characterization and relevant literature retrieval, Method Design, where specialized agents collaboratively develop optimized modeling strategies, and Experiment Execution for automated generation of code. The agents in the Design module are separated into experts with differing perspectives and a central moderator, and have to collaboratively exchange solutions until they achieve a reasonable consensus. We demonstrate CellForge's capabilities in single-cell perturbation prediction, using six diverse datasets that encompass gene knockouts, drug treatments, and cytokine stimulations across multiple modalities. CellForge consistently outperforms task-specific state-of-the-art methods. Overall, CellForge demonstrates how iterative interaction between LLM agents with differing perspectives provides better solutions than directly addressing a modeling challenge. Our code is publicly available at https://github.com/gersteinlab/CellForge.

[Arxiv](https://arxiv.org/abs/2508.02276)