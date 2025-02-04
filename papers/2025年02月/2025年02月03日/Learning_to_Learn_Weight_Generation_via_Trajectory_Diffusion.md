# 通过轨迹扩散学习权重生成

发布时间：2025年02月03日

`其他

理由：这篇论文主要讨论的是扩散算法在权重生成领域的应用，特别是与元学习结合以生成未知任务的权重。虽然提到了大规模语言模型微调，但核心内容并不直接涉及大型语言模型（LLM）的理论、应用、Agent或RAG（Retrieval-Augmented Generation）。因此，将其分类为“其他”更为合适。` `机器学习` `多任务学习`

> Learning to Learn Weight Generation via Trajectory Diffusion

# 摘要

> 扩散算法在权重生成领域崭露头角，尤其适用于多任务学习等需要频繁更新权重的场景。然而，现有方案在跨任务迁移能力上表现欠佳，且仅依赖最优权重作为训练样本，忽视了优化过程中其他权重的潜力。为此，我们提出了Lt-Di，它将扩散算法与元学习巧妙结合，为未知任务生成权重。我们还创新性地将普通扩散算法升级为轨迹扩散算法，充分利用优化轨迹上的权重信息。轨迹扩散通过将长扩散链拆分为多个短链，显著提升了训练和推理效率。我们深入分析了权重生成范式的收敛特性，并在不增加时间成本的前提下优化了收敛效率。实验结果显示，Lt-Di在零-shot、少-shot学习、多领域泛化及大规模语言模型微调等任务中均展现出更高的准确性，同时大幅降低了计算开销。代码已开源：https://github.com/tuantuange/Lt-Di。

> Diffusion-based algorithms have emerged as promising techniques for weight generation, particularly in scenarios like multi-task learning that require frequent weight updates. However, existing solutions suffer from limited cross-task transferability. In addition, they only utilize optimal weights as training samples, ignoring the value of other weights in the optimization process. To address these issues, we propose Lt-Di, which integrates the diffusion algorithm with meta-learning to generate weights for unseen tasks. Furthermore, we extend the vanilla diffusion algorithm into a trajectory diffusion algorithm to utilize other weights along the optimization trajectory. Trajectory diffusion decomposes the entire diffusion chain into multiple shorter ones, improving training and inference efficiency. We analyze the convergence properties of the weight generation paradigm and improve convergence efficiency without additional time overhead. Our experiments demonstrate Lt-Di's higher accuracy while reducing computational overhead across various tasks, including zero-shot and few-shot learning, multi-domain generalization, and large-scale language model fine-tuning.Our code is released at https://github.com/tuantuange/Lt-Di.

[Arxiv](https://arxiv.org/abs/2502.01117)