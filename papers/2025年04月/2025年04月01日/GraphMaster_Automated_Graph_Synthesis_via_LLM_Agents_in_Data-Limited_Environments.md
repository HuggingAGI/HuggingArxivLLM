# GraphMaster：数据受限环境下的LLM驱动自动图合成

发布时间：2025年04月01日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来生成语义丰富且结构完整的图数据，特别是在数据受限的环境中。论文中提到的GraphMaster框架协调了四个专门的LLM智能体，这表明它主要关注的是如何应用LLMs来解决特定的图数据合成问题。因此，这篇论文属于LLM应用的范畴。` `数据合成` `人工智能`

> GraphMaster: Automated Graph Synthesis via LLM Agents in Data-Limited Environments

# 摘要

> 基础模型时代彻底改变了AI研究的面貌，但图基础模型（GFMs）的发展仍受限于大规模图语料库的匮乏。传统图数据合成技术主要关注简单的结构操作，缺乏生成语义丰富且具有实际意义文本属性节点的能力，这对实际应用构成了关键性限制。尽管大型语言模型（LLMs）在文本生成方面表现卓越，但受限于上下文窗口限制、幻觉现象以及结构一致性难题，直接将其应用于图合成面临诸多阻碍。为了解决这些问题，我们推出了GraphMaster——首个专为数据受限环境下的图数据合成设计的多智能体框架。GraphMaster协调四位专门的LLM智能体（管理者、感知器、增强器和评估器），通过迭代优化合成过程，确保语义连贯性和结构完整性。为了严格评估我们的方法，我们创建了六种标准图基准的新“子”变体，这些变体特意设计用于在现实约束下测试合成能力。此外，我们还开发了一种全新的可解释性评估框架，结合人工评估与基于Grassmannian流形的原理性分析，提供语义连贯性的定性和定量度量。实验结果表明，GraphMaster在多个数据集上显著超越传统合成方法，为在数据稀缺环境下推进图基础模型的发展奠定了坚实基础。

> The era of foundation models has revolutionized AI research, yet Graph Foundation Models (GFMs) remain constrained by the scarcity of large-scale graph corpora. Traditional graph data synthesis techniques primarily focus on simplistic structural operations, lacking the capacity to generate semantically rich nodes with meaningful textual attributes: a critical limitation for real-world applications. While large language models (LLMs) demonstrate exceptional text generation capabilities, their direct application to graph synthesis is impeded by context window limitations, hallucination phenomena, and structural consistency challenges. To address these issues, we introduce GraphMaster, the first multi-agent framework specifically designed for graph data synthesis in data-limited environments. GraphMaster orchestrates four specialized LLM agents (Manager, Perception, Enhancement, and Evaluation) that collaboratively optimize the synthesis process through iterative refinement, ensuring both semantic coherence and structural integrity. To rigorously evaluate our approach, we create new data-limited "Sub" variants of six standard graph benchmarks, specifically designed to test synthesis capabilities under realistic constraints. Additionally, we develop a novel interpretability assessment framework that combines human evaluation with a principled Grassmannian manifold-based analysis, providing both qualitative and quantitative measures of semantic coherence. Experimental results demonstrate that GraphMaster significantly outperforms traditional synthesis methods across multiple datasets, establishing a strong foundation for advancing GFMs in data-scarce environments.

[Arxiv](https://arxiv.org/abs/2504.00711)