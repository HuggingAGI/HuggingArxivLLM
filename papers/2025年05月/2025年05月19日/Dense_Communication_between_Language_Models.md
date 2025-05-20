# 语言模型间的高效沟通

发布时间：2025年05月19日

`LLM应用` `人工智能` `分布式系统`

> Dense Communication between Language Models

# 摘要

> 当模块化组件与低级智能结合产生高级智能时，许多研究通过结合大型语言模型（LLMs）来实现集体智能。这种结合依赖于在LLMs之间建立通信机制。尽管现有系统主要借助自然语言来实现这一目标，但本研究提出了一种全新的范式——LLMs之间的直接密集向量通信。我们的方法巧妙地去除了LLMs交互过程中不必要的嵌入与解嵌入步骤，从而实现了信息传递的高效性、优化路径的完全可微分性，以及超越人类直觉的潜力探索。我们以这些精简的LLMs为节点，将可优化的seq2seq模块作为连接边，构建了一个结构类似多层感知机（MLPs）的LMNet。通过采用较小规模的预训练LLMs作为节点，我们成功训练出一个LMNet，其性能与同规模的LLMs相媲美，而训练成本却不到0.1%。这一突破为通用智能的扩展提供了全新视角，避免了从零开始训练单体LLM的局限。此外，该方法的灵活性使其能够应用于其他场景，如利用有限数据定制LLMs，充分展现了其广泛的应用前景。

> As higher-level intelligence emerges from the combination of modular components with lower-level intelligence, many works combines Large Language Models (LLMs) for collective intelligence. Such combination is achieved by building communications among LLMs. While current systems primarily facilitate such communication through natural language, this paper proposes a novel paradigm of direct dense vector communication between LLMs. Our approach eliminates the unnecessary embedding and de-embedding steps when LLM interact with another, enabling more efficient information transfer, fully differentiable optimization pathways, and exploration of capabilities beyond human heuristics. We use such stripped LLMs as vertexes and optimizable seq2seq modules as edges to construct LMNet, with similar structure as MLPs. By utilizing smaller pre-trained LLMs as vertexes, we train a LMNet that achieves comparable performance with LLMs in similar size with only less than 0.1% training cost. This offers a new perspective on scaling for general intelligence rather than training a monolithic LLM from scratch. Besides, the proposed method can be used for other applications, like customizing LLM with limited data, showing its versatility.

[Arxiv](https://arxiv.org/abs/2505.12741)