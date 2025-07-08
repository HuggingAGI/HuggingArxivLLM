# 药物发现中模块化任务执行的大型语言模型代理

发布时间：2025年06月25日

`LLM应用` `药物发现` `分子设计`

> Large Language Model Agent for Modular Task Execution in Drug Discovery

# 摘要

> 我们提出了一种由大型语言模型（LLMs）驱动的模块化框架，该框架能够自动化并简化早期药物发现管道中的关键任务。通过结合LLM推理与领域特定工具，该框架实现了生物医学数据检索、领域特定问题解答、分子生成、性质预测、具有性质感知的分子优化以及3D蛋白质-配体结构生成。在一项针对淋巴细胞白血病中BCL-2蛋白的案例研究中，该智能体自主检索了相关的生物分子信息——包括FASTA序列、SMILES表示和文献——并以比标准LLMs更高的上下文准确性回答了机制性问题。随后，它生成了化学多样性种子分子，并预测了67个与ADMET相关的性质，这些预测指导了迭代分子优化。在两次优化轮次中，QED > 0.6的分子数量从34增加到55，而在194个分子池中，至少通过五项药物类规则中的四项的分子数量从29增加到52。该框架还利用Boltz-2生成了3D蛋白质-配体复合物，并为候选化合物提供了快速结合亲和力估计。这些结果表明，该方法有效支持分子筛选、优先排序和结构评估。其模块化设计使不断发展的工具和模型能够灵活集成，为人工智能辅助的治疗发现提供了可扩展的基础。

> We present a modular framework powered by large language models (LLMs) that automates and streamlines key tasks across the early-stage computational drug discovery pipeline. By combining LLM reasoning with domain-specific tools, the framework performs biomedical data retrieval, domain-specific question answering, molecular generation, property prediction, property-aware molecular refinement, and 3D protein-ligand structure generation. In a case study targeting BCL-2 in lymphocytic leukemia, the agent autonomously retrieved relevant biomolecular information-including FASTA sequences, SMILES representations, and literature-and answered mechanistic questions with improved contextual accuracy over standard LLMs. It then generated chemically diverse seed molecules and predicted 67 ADMET-related properties, which guided iterative molecular refinement. Across two refinement rounds, the number of molecules with QED > 0.6 increased from 34 to 55, and those passing at least four out of five empirical drug-likeness rules rose from 29 to 52, within a pool of 194 molecules. The framework also employed Boltz-2 to generate 3D protein-ligand complexes and provide rapid binding affinity estimates for candidate compounds. These results demonstrate that the approach effectively supports molecular screening, prioritization, and structure evaluation. Its modular design enables flexible integration of evolving tools and models, providing a scalable foundation for AI-assisted therapeutic discovery.

[Arxiv](https://arxiv.org/abs/2507.02925)