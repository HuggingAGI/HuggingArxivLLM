# 逻辑增强生成提升多模态类比推理能力

发布时间：2025年04月15日

`LLM应用` `知识图谱`

> Enhancing multimodal analogical reasoning with Logic Augmented Generation

# 摘要

> 大型语言模型在多种任务中展现出强大的能力，但机器缺乏对物理世界的主动体验，导致从自然语言中自动提取隐性知识仍是一个重大挑战。面对这一现状，语义知识图谱可作为概念空间，引导自动文本生成推理过程，以实现更高效且可解释的结果。本文提出了一种结合语义知识图谱显式表示和提示启发的逻辑增强生成（LAG）框架，通过提取隐性类比连接来实现更高效的推理。该方法生成扩展的知识图谱三元组，表示隐性含义，使系统能够对无标签的多模态数据进行推理，不受领域限制。我们通过四个数据集上的三个隐喻检测和理解任务验证了我们的工作，因为这些任务需要深入的类比推理能力。结果显示，这种集成方法超越了当前基线，在理解视觉隐喻方面甚至优于人类，并实现了更可解释的推理过程，尽管在隐喻理解方面仍存在固有局限，特别是在领域特定隐喻方面。此外，我们提出了一种全面的错误分析，探讨了隐喻标注和当前评估方法的问题。

> Recent advances in Large Language Models have demonstrated their capabilities across a variety of tasks. However, automatically extracting implicit knowledge from natural language remains a significant challenge, as machines lack active experience with the physical world. Given this scenario, semantic knowledge graphs can serve as conceptual spaces that guide the automated text generation reasoning process to achieve more efficient and explainable results. In this paper, we apply a logic-augmented generation (LAG) framework that leverages the explicit representation of a text through a semantic knowledge graph and applies it in combination with prompt heuristics to elicit implicit analogical connections. This method generates extended knowledge graph triples representing implicit meaning, enabling systems to reason on unlabeled multimodal data regardless of the domain. We validate our work through three metaphor detection and understanding tasks across four datasets, as they require deep analogical reasoning capabilities. The results show that this integrated approach surpasses current baselines, performs better than humans in understanding visual metaphors, and enables more explainable reasoning processes, though still has inherent limitations in metaphor understanding, especially for domain-specific metaphors. Furthermore, we propose a thorough error analysis, discussing issues with metaphorical annotations and current evaluation methods.

[Arxiv](https://arxiv.org/abs/2504.11190)