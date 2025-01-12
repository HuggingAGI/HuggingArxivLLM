# 借助SemanticLens深入理解并验证大型AI模型的机制

发布时间：2025年01月09日

`LLM理论

理由：这篇论文主要讨论了一种用于神经网络的通用解释方法SemanticLens，它通过将神经网络的组件映射到语义结构化的多模态空间中来解释和理解AI模型的内部工作机制。这种方法旨在提高AI模型的可解释性和可验证性，从而增强对AI系统的信任。虽然论文中提到了基础模型（如CLIP），但重点在于解释和理解AI模型的内部机制，而不是直接应用或扩展大型语言模型（LLM）的功能。因此，这篇论文更适合归类为“LLM理论”，因为它涉及对AI模型的理论理解和解释方法的研究。` `人工智能` `模型解释`

> Mechanistic understanding and validation of large AI models with SemanticLens

# 摘要

> 与飞机等人类设计的系统不同，这些系统中每个组件的作用和依赖关系都被充分理解，而AI模型的内部工作机制在很大程度上仍然是不透明的，这阻碍了可验证性并削弱了信任。本文介绍了SemanticLens，一种用于神经网络的通用解释方法，它将组件（例如单个神经元）编码的隐藏知识映射到基础模型（如CLIP）的语义结构化的多模态空间中。在这个空间中，可以实现独特的操作，包括（i）通过文本搜索识别编码特定概念的神经元，（ii）系统分析和比较模型表示，（iii）自动标记神经元并解释其功能角色，以及（iv）审计以验证决策是否符合要求。SemanticLens完全可扩展且无需人工输入，被证明在调试和验证、总结模型知识、使推理与期望一致（例如，遵守黑色素瘤分类中的ABCDE规则）以及检测与虚假相关性及其相关训练数据相关的组件方面是有效的。通过实现组件级别的理解和验证，所提出的方法有助于弥合AI模型与传统工程系统之间的“信任鸿沟”。我们在https://github.com/jim-berend/semanticlens上提供了SemanticLens的代码，并在https://semanticlens.hhi-research-insights.eu上提供了一个演示。

> Unlike human-engineered systems such as aeroplanes, where each component's role and dependencies are well understood, the inner workings of AI models remain largely opaque, hindering verifiability and undermining trust. This paper introduces SemanticLens, a universal explanation method for neural networks that maps hidden knowledge encoded by components (e.g., individual neurons) into the semantically structured, multimodal space of a foundation model such as CLIP. In this space, unique operations become possible, including (i) textual search to identify neurons encoding specific concepts, (ii) systematic analysis and comparison of model representations, (iii) automated labelling of neurons and explanation of their functional roles, and (iv) audits to validate decision-making against requirements. Fully scalable and operating without human input, SemanticLens is shown to be effective for debugging and validation, summarizing model knowledge, aligning reasoning with expectations (e.g., adherence to the ABCDE-rule in melanoma classification), and detecting components tied to spurious correlations and their associated training data. By enabling component-level understanding and validation, the proposed approach helps bridge the "trust gap" between AI models and traditional engineered systems. We provide code for SemanticLens on https://github.com/jim-berend/semanticlens and a demo on https://semanticlens.hhi-research-insights.eu.

[Arxiv](https://arxiv.org/abs/2501.05398)