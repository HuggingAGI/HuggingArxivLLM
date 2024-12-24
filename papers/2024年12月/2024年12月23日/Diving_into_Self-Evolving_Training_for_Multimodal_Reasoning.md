# 深入探索多模态推理的自进化训练

发布时间：2024年12月23日

`LLM应用` `多模态推理` `自进化训练`

> Diving into Self-Evolving Training for Multimodal Reasoning

# 摘要

> 推理能力对大型多模态模型（LMMs）而言不可或缺。在缺乏多模态思维链标注数据的情况下，自进化训练（即模型从自身输出中学习）已成为提升推理能力的有效且可扩展的途径。尽管其应用日益广泛，但对于自进化训练，尤其是在多模态推理的情境中，全面的理解仍十分有限。在本文中，我们深入探究了多模态推理自进化训练的复杂性，明确了三个关键因素：训练方法、奖励模型和提示变化。我们对每个因素进行了系统研究，并探讨了不同配置对训练效果的影响。我们的分析得出了每个因素的一系列最佳实践，旨在优化多模态推理。此外，我们还探讨了训练过程中的自进化动态以及自动平衡机制对提升性能的作用。经过一系列研究，我们给出了多模态推理自进化训练的最终方案，将这些设计选择封装在一个名为 MSTaR（用于推理的多模态自进化训练）的框架中，该框架对不同规模的模型在各类基准测试中普遍有效，例如在 MiniCPM-V-2.5（8B）、Phi-3.5-Vision（4B）和 InternVL2（2B）上，显著超越了预进化模型，且未使用额外的人工标注。我们认为，此项研究填补了对多模态推理自进化训练理解的重大空缺，并为未来研究提供了有力的框架。我们的策略和奖励模型以及收集的数据已发布，以推动多模态推理的进一步探索。

> Reasoning ability is essential for Large Multimodal Models (LMMs). In the absence of multimodal chain-of-thought annotated data, self-evolving training, where the model learns from its own outputs, has emerged as an effective and scalable approach for enhancing reasoning abilities. Despite its growing usage, a comprehensive understanding of self-evolving training, particularly in the context of multimodal reasoning, remains limited. In this paper, we delve into the intricacies of self-evolving training for multimodal reasoning, pinpointing three key factors: Training Method, Reward Model, and Prompt Variation. We systematically examine each factor and explore how various configurations affect the training's effectiveness. Our analysis leads to a set of best practices for each factor, aimed at optimizing multimodal reasoning. Furthermore, we explore the Self-Evolution Dynamics during training and the impact of automatic balancing mechanisms in boosting performance. After all the investigations, we present a final recipe for self-evolving training in multimodal reasoning, encapsulating these design choices into a framework we call MSTaR (Multimodal Self-evolving Training for Reasoning), which is universally effective for models with different sizes on various benchmarks, e.g., surpassing the pre-evolved model significantly on 5 multimodal reasoning benchmarks without using additional human annotations, as demonstrated on MiniCPM-V-2.5 (8B), Phi-3.5-Vision (4B) and InternVL2 (2B). We believe this study fills a significant gap in the understanding of self-evolving training for multimodal reasoning and offers a robust framework for future research. Our policy and reward models, as well as the collected data, is released to facilitate further investigation in multimodal reasoning.

[Arxiv](https://arxiv.org/abs/2412.17451)