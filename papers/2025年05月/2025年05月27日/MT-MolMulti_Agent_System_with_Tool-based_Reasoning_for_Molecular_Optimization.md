# MT-Mol：结合基于工具推理的多智能体系统用于分子优化

发布时间：2025年05月27日

`LLM应用

摘要中描述了将大型语言模型（LLMs）应用于分子优化领域的研究，具体通过MT-Mol框架整合化学工具和角色专业化代理，展示了在分子优化中的应用成果。因此，这篇论文属于LLM应用类别。` `药物开发`

> MT-Mol:Multi Agent System with Tool-based Reasoning for Molecular Optimization

# 摘要

> 大型语言模型 (LLMs) 在分子优化领域展现出巨大潜力，能够整合外部化学工具并促进协作交互，从而逐步优化分子候选。然而，其潜力尚未得到充分挖掘，特别是在结构化推理、可解释性及全面工具支持的分子优化方面。为填补这一空白，我们推出了 MT-Mol，这是一个基于工具引导推理和角色专业化 LLM 代理的分子优化多智能体框架。我们的系统整合了全面的 RDKit 工具，涵盖结构描述符、电子和拓扑特性、基于片段的功能基团、分子表示以及各种化学性质五大领域。每个领域由一位专家分析师代理负责，提取相关工具并提供可解释的、基于化学的反馈。通过分析师代理与分子生成科学家、推理输出验证器及评审代理的协作，MT-Mol 实现工具对齐和逐步推理，生成优化分子。最终，我们在 PMO-1K 基准测试的 23 项任务中有 17 项达到了最先进的性能水平。

> Large language models (LLMs) have large potential for molecular optimization, as they can gather external chemistry tools and enable collaborative interactions to iteratively refine molecular candidates. However, this potential remains underexplored, particularly in the context of structured reasoning, interpretability, and comprehensive tool-grounded molecular optimization. To address this gap, we introduce MT-Mol, a multi-agent framework for molecular optimization that leverages tool-guided reasoning and role-specialized LLM agents. Our system incorporates comprehensive RDKit tools, categorized into five distinct domains: structural descriptors, electronic and topological features, fragment-based functional groups, molecular representations, and miscellaneous chemical properties. Each category is managed by an expert analyst agent, responsible for extracting task-relevant tools and enabling interpretable, chemically grounded feedback. MT-Mol produces molecules with tool-aligned and stepwise reasoning through the interaction between the analyst agents, a molecule-generating scientist, a reasoning-output verifier, and a reviewer agent. As a result, we show that our framework shows the state-of-the-art performance of the PMO-1K benchmark on 17 out of 23 tasks.

[Arxiv](https://arxiv.org/abs/2505.20820)