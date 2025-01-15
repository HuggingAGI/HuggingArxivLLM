# 多模态AI助手：指令驱动的单细胞分析

发布时间：2025年01月14日

`LLM应用

理由：这篇论文介绍了InstructCell，一个多模态AI助手，利用自然语言作为媒介来实现单细胞分析。它结合了文本指令和单细胞RNA测序数据，开发了一种多模态细胞语言架构，能够处理和理解这两种模态。InstructCell通过自然语言指令完成关键任务，如细胞类型注释、条件性伪细胞生成和药物敏感性预测。这表明该论文主要关注如何将大型语言模型（LLM）应用于生命科学领域的具体任务，因此属于“LLM应用”分类。` `生命科学` `单细胞分析`

> A Multi-Modal AI Copilot for Single-Cell Analysis with Instruction Following

# 摘要

> 大型语言模型在解析复杂自然语言指令方面表现出色，使其能够胜任多种任务。在生命科学领域，单细胞RNA测序（scRNA-seq）数据被誉为“细胞生物学的语言”，它能在单细胞水平上捕捉复杂的基因表达模式。然而，传统工具与这种“语言”的交互往往效率低下且不够直观，给研究人员带来了诸多挑战。为此，我们推出了InstructCell，这是一款多模态AI助手，它利用自然语言作为媒介，实现了更直接、灵活的单细胞分析。我们构建了一个全面的多模态指令数据集，将文本指令与来自不同组织和物种的scRNA-seq数据相结合。基于此，我们开发了一种多模态细胞语言架构，能够同时处理和理解这两种模态。InstructCell使研究人员能够通过简单的自然语言指令完成关键任务，如细胞类型注释、条件性伪细胞生成和药物敏感性预测。广泛的评估表明，InstructCell不仅始终达到或超越现有单细胞基础模型的性能，还能适应各种实验条件。更重要的是，InstructCell为探索复杂的单细胞数据提供了一个直观且易于使用的工具，降低了技术门槛，助力研究人员获得更深入的生物学见解。

> Large language models excel at interpreting complex natural language instructions, enabling them to perform a wide range of tasks. In the life sciences, single-cell RNA sequencing (scRNA-seq) data serves as the "language of cellular biology", capturing intricate gene expression patterns at the single-cell level. However, interacting with this "language" through conventional tools is often inefficient and unintuitive, posing challenges for researchers. To address these limitations, we present InstructCell, a multi-modal AI copilot that leverages natural language as a medium for more direct and flexible single-cell analysis. We construct a comprehensive multi-modal instruction dataset that pairs text-based instructions with scRNA-seq profiles from diverse tissues and species. Building on this, we develop a multi-modal cell language architecture capable of simultaneously interpreting and processing both modalities. InstructCell empowers researchers to accomplish critical tasks-such as cell type annotation, conditional pseudo-cell generation, and drug sensitivity prediction-using straightforward natural language commands. Extensive evaluations demonstrate that InstructCell consistently meets or exceeds the performance of existing single-cell foundation models, while adapting to diverse experimental conditions. More importantly, InstructCell provides an accessible and intuitive tool for exploring complex single-cell data, lowering technical barriers and enabling deeper biological insights.

[Arxiv](https://arxiv.org/abs/2501.08187)