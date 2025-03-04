# 记忆的精准定位：一种细粒度神经元级知识编辑技术，专为大型语言模型设计

发布时间：2025年03月02日

`LLM理论` `知识编辑` `大型语言模型`

> Precise Localization of Memories: A Fine-grained Neuron-level Knowledge Editing Technique for LLMs

# 摘要

> 知识编辑旨在更新大型语言模型中的过时信息。定位后编辑的方法通常通过因果追踪来识别负责回忆实体事实知识的模块。然而，我们发现这些方法通常仅对主体实体的变化敏感，导致它们在应对关系变化时效果不佳。这一局限性导致编辑定位性较差，可能使无关或不准确的事实持续存在，最终影响大型语言模型的可靠性。我们认为这一问题源于知识定位的精度不足。为解决此问题，我们提出了一种细粒度神经元级知识编辑方法（FiNE），在不影响整体成功率的情况下提升编辑定位性。通过精确识别和修改前馈网络中的特定神经元，FiNE显著改善了知识定位和编辑效果。定量实验表明，与现有技术相比，FiNE能够更高效地实现更好的整体性能，为大型语言模型中知识的定位和修改提供了新的见解。

> Knowledge editing aims to update outdated information in Large Language Models (LLMs). A representative line of study is locate-then-edit methods, which typically employ causal tracing to identify the modules responsible for recalling factual knowledge about entities. However, we find these methods are often sensitive only to changes in the subject entity, leaving them less effective at adapting to changes in relations. This limitation results in poor editing locality, which can lead to the persistence of irrelevant or inaccurate facts, ultimately compromising the reliability of LLMs. We believe this issue arises from the insufficient precision of knowledge localization. To address this, we propose a Fine-grained Neuron-level Knowledge Editing (FiNE) method that enhances editing locality without affecting overall success rates. By precisely identifying and modifying specific neurons within feed-forward networks, FiNE significantly improves knowledge localization and editing. Quantitative experiments demonstrate that FiNE efficiently achieves better overall performance compared to existing techniques, providing new insights into the localization and modification of knowledge within LLMs.

[Arxiv](https://arxiv.org/abs/2503.01090)