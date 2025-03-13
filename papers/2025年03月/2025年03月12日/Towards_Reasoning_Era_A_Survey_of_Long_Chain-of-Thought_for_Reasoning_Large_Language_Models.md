# 迈向推理时代：长链思维推理大型语言模型综述

发布时间：2025年03月12日

`LLM理论` `人工智能` `推理技术`

> Towards Reasoning Era: A Survey of Long Chain-of-Thought for Reasoning Large Language Models

# 摘要

> 近期，基于大型语言模型的推理技术（如 OpenAI-O1 和 DeepSeek-R1）在数学与编程等复杂领域展现出了令人惊叹的能力。这些模型的成功，关键在于其运用了长链式思考（Long CoT）的特性，从而显著提升了推理能力并能够解决复杂问题。然而，尽管取得了这些进展，目前仍缺乏对 Long CoT 的全面综述，这不仅限制了我们对其与传统短链式思考（Short CoT）区别的理解，也使得关于“过度思考”和“推理时扩展”等议题的讨论变得更加复杂。本综述旨在通过提供一个统一的视角来填补这一空白。 (1) 首先，我们明确了 Long CoT 与 Short CoT 的区别，并提出了一种新的分类体系来涵盖当前的推理范式。 (2) 接着，我们深入探讨了 Long CoT 的三大核心特征：深入推理、广泛探索和可行的反思，这些特征使模型能够处理更复杂的任务，并与传统的 Short CoT 相比，生成更高效、连贯的结果。 (3) 然后，我们重点分析了 Long CoT 中的关键现象，如过度思考和推理时扩展，揭示了这些机制在实际应用中的表现。 (4) 最后，我们指出了当前研究中的空白，并展望了未来的发展方向，包括多模态推理的整合、推理效率的提升以及知识框架的优化。通过系统性的梳理与总结，本综述希望为未来的研究提供灵感，并推动人工智能领域逻辑推理能力的进一步发展。

> Recent advancements in reasoning with large language models (RLLMs), such as OpenAI-O1 and DeepSeek-R1, have demonstrated their impressive capabilities in complex domains like mathematics and coding. A central factor in their success lies in the application of long chain-of-thought (Long CoT) characteristics, which enhance reasoning abilities and enable the solution of intricate problems. However, despite these developments, a comprehensive survey on Long CoT is still lacking, limiting our understanding of its distinctions from traditional short chain-of-thought (Short CoT) and complicating ongoing debates on issues like "overthinking" and "test-time scaling." This survey seeks to fill this gap by offering a unified perspective on Long CoT. (1) We first distinguish Long CoT from Short CoT and introduce a novel taxonomy to categorize current reasoning paradigms. (2) Next, we explore the key characteristics of Long CoT: deep reasoning, extensive exploration, and feasible reflection, which enable models to handle more complex tasks and produce more efficient, coherent outcomes compared to the shallower Short CoT. (3) We then investigate key phenomena such as the emergence of Long CoT with these characteristics, including overthinking, and test-time scaling, offering insights into how these processes manifest in practice. (4) Finally, we identify significant research gaps and highlight promising future directions, including the integration of multi-modal reasoning, efficiency improvements, and enhanced knowledge frameworks. By providing a structured overview, this survey aims to inspire future research and further the development of logical reasoning in artificial intelligence.

[Arxiv](https://arxiv.org/abs/2503.09567)