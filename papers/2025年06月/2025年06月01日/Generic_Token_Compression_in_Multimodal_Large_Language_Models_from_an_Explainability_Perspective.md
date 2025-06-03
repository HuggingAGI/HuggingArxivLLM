# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月01日

`LLM应用` `视觉处理`

> Generic Token Compression in Multimodal Large Language Models from an Explainability Perspective

# 摘要

> 现有跨模态大语言模型（MLLMs）处理大量视觉标记，导致显著的计算成本和低效。先前研究假设浅层中的所有视觉标记对LLMs至关重要，因此标记压缩通常在中间层进行。然而，我们发现一个有趣的现象：通过适当选择，标记压缩可以在LLMs的输入阶段实现，且性能损失微乎其微。具体而言，可解释性方法能够有效评估每个视觉标记的重要性，从而为标记压缩提供良好指导。我们提出通过学习从LLMs首层注意力图到解释结果的映射，从而避免完整的推断过程并促进实际部署。这一映射可以通过简单且轻量的卷积网络学习，其训练高效且独立于MLLMs。在涵盖三个领先MLLMs（Qwen2-VL、LLaVA-OneVision 和 VILA1.5）的10个图像和视频基准上进行的广泛实验，验证了我们方法的有效性。例如，在所有基准中对所有三种MLLMs保留超过96%的原始性能的同时，压缩50%的视觉标记。此外，该方法展现出强大的泛化能力，即使推理中的标记数量远超训练时的数量，仍能保持良好效果。

> Existing Multimodal Large Language Models (MLLMs) process a large number of visual tokens, leading to significant computational costs and inefficiency. Previous works generally assume that all visual tokens are necessary in the shallow layers of LLMs, and therefore token compression typically occurs in intermediate layers. In contrast, our study reveals an interesting insight: with proper selection, token compression is feasible at the input stage of LLM with negligible performance loss. Specifically, we reveal that explainability methods can effectively evaluate the importance of each visual token with respect to the given instruction, which can well guide the token compression. Furthermore, we propose to learn a mapping from the attention map of the first LLM layer to the explanation results, thereby avoiding the need for a full inference pass and facilitating practical deployment. Interestingly, this mapping can be learned using a simple and lightweight convolutional network, whose training is efficient and independent of MLLMs. Extensive experiments on 10 image and video benchmarks across three leading MLLMs (Qwen2-VL, LLaVA-OneVision, and VILA1.5) demonstrate the effectiveness of our approach, e.g., pruning 50% visual tokens while retaining more than 96% of the original performance across all benchmarks for all these three MLLMs. It also exhibits strong generalization, even when the number of tokens in inference far exceeds that used in training.

[Arxiv](https://arxiv.org/abs/2506.01097)