# UniMoD：高效统一的多模态变压器，结合深度混合

发布时间：2025年02月10日

`LLM应用` `多模态` `模型优化`

> UniMoD: Efficient Unified Multimodal Transformers with Mixture-of-Depths

# 摘要

> 统一的多模态变压器模型在同一参数空间内同时处理生成和理解任务，吸引了越来越多的研究关注。然而，由于冗余tokens和繁重的注意力计算，训练这些模型的成本依然较高。过去研究表明，token剪枝方法如深度混合（MoD）可显著提升计算效率，但直接将其应用于统一模型会导致性能不佳，因不同任务的token冗余程度不同。我们通过分析注意力权重模式、评估层的重要性和token冗余、以及分析任务间的相互作用，发现token冗余主要受任务和层的影响。基于此，我们提出UniMoD，一种任务感知的token剪枝方法，为每个任务配备独立路由模块，确定可剪枝tokens。应用于Show-o和Emu3，分别将训练FLOPs减少约15%和40%，同时在多个基准测试中保持或提升性能。代码将在（https://github.com/showlab/UniMoD）发布。

> Unified multimodal transformers, which handle both generation and understanding tasks within a shared parameter space, have received increasing attention in recent research. Although various unified transformers have been proposed, training these models is costly due to redundant tokens and heavy attention computation. In the past, studies on large language models have demonstrated that token pruning methods, such as Mixture of Depths (MoD), can significantly improve computational efficiency. MoD employs a router to select the most important ones for processing within a transformer layer. However, directly applying MoD-based token pruning to unified transformers will result in suboptimal performance because different tasks exhibit varying levels of token redundancy. In our work, we analyze the unified transformers by (1) examining attention weight patterns, (2) evaluating the layer importance and token redundancy, and (3) analyzing task interactions. Our findings reveal that token redundancy is primarily influenced by different tasks and layers. Building on these findings, we introduce UniMoD, a task-aware token pruning method that employs a separate router for each task to determine which tokens should be pruned. We apply our method to Show-o and Emu3, reducing training FLOPs by approximately 15% in Show-o and 40% in Emu3, while maintaining or improving performance on several benchmarks. Code will be released at https://github.com/showlab/UniMoD.

[Arxiv](https://arxiv.org/abs/2502.06474)