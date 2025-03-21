# # **摘要**  
    最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月20日

`LLM应用

摘要中的论文提出了一种新的框架，将大型语言模型应用于3D结构生成与理解任务，展示了其在多个微观3D GU任务中的有效性，并超越了之前的最优模型。这属于将LLM应用于特定任务的范畴。` `3D生成与理解` `分子建模`

> Uni-3DAR: Unified 3D Generation and Understanding via Autoregression on Compressed Spatial Tokens

# 摘要

> 近期研究显示，大型语言模型及其多模态扩展通过自回归下一个词预测，在统一生成与理解方面取得了显著成效。然而，尽管3D结构生成与理解（3D GU）在AI科学中至关重要，这些任务却大多独立发展，自回归方法的应用仍十分有限。为解决这一问题，我们提出了Uni-3DAR——一个通过自回归预测无缝整合3D GU任务的统一框架。其核心技术采用创新的分层标记化方法，利用八叉树压缩三维空间，充分挖掘三维结构的固有稀疏性。随后，该框架进一步采用额外的标记化处理，捕捉微观三维结构中的精细细节，如原子类型和精确空间坐标等关键属性。我们还提出了两项优化策略：首先是两级子树压缩策略，将八叉树标记序列压缩高达8倍；其次是针对动态变化标记位置的遮蔽式下一个词预测机制，显著提升了模型性能。通过结合这些策略，Uni-3DAR成功将多样化的3D GU任务统一在一个自回归框架内。在分子、蛋白质、聚合物和晶体等多类微观3D GU任务的广泛实验中，其有效性和通用性得到了充分验证。值得注意的是，Uni-3DAR不仅大幅超越了先前的最优扩散模型，实现了高达256%的相对提升，同时推理速度也快达21.8倍。代码已公开，访问地址为https://github.com/dptech-corp/Uni-3DAR。


> Recent advancements in large language models and their multi-modal extensions have demonstrated the effectiveness of unifying generation and understanding through autoregressive next-token prediction. However, despite the critical role of 3D structural generation and understanding ({3D GU}) in AI for science, these tasks have largely evolved independently, with autoregressive methods remaining underexplored. To bridge this gap, we introduce Uni-3DAR, a unified framework that seamlessly integrates {3D GU} tasks via autoregressive prediction. At its core, Uni-3DAR employs a novel hierarchical tokenization that compresses 3D space using an octree, leveraging the inherent sparsity of 3D structures. It then applies an additional tokenization for fine-grained structural details, capturing key attributes such as atom types and precise spatial coordinates in microscopic 3D structures. We further propose two optimizations to enhance efficiency and effectiveness. The first is a two-level subtree compression strategy, which reduces the octree token sequence by up to 8x. The second is a masked next-token prediction mechanism tailored for dynamically varying token positions, significantly boosting model performance. By combining these strategies, Uni-3DAR successfully unifies diverse {3D GU} tasks within a single autoregressive framework. Extensive experiments across multiple microscopic {3D GU} tasks, including molecules, proteins, polymers, and crystals, validate its effectiveness and versatility. Notably, Uni-3DAR surpasses previous state-of-the-art diffusion models by a substantial margin, achieving up to 256\% relative improvement while delivering inference speeds up to 21.8x faster. The code is publicly available at https://github.com/dptech-corp/Uni-3DAR.

[Arxiv](https://arxiv.org/abs/2503.16278)