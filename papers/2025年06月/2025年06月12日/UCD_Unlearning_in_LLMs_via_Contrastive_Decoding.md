# UCD：利用对比解码实现LLM的遗忘机制

发布时间：2025年06月12日

`LLM理论

理由：这篇论文探讨了如何通过对比解码和辅助模型来改进大型语言模型的无学习方法，属于模型训练和优化的理论研究。` `人工智能`

> UCD: Unlearning in LLMs via Contrastive Decoding

# 摘要

> 机器无学习的目标是从大型语言模型（LLMs）中移除特定信息，如敏感或不受欢迎的内容，同时保持整体性能。我们提出了一种基于推理时的无学习算法，使用对比解码，借助两个辅助的小模型，一个是在不遗忘数据集的情况下训练的，另一个是在遗忘数据集的情况下训练的，通过它们在推理时的差异来引导原模型的输出。我们的策略显著改善了无学习效果与模型实用性之间的权衡。我们在两个无学习基准测试，TOFU和MUSE上评估了我们的方法。结果显示，与先前的方法相比，我们的方法在遗忘质量和保留性能方面都有显著提升，这表明引入对比解码可以为大规模模型中的概念无学习提供一个高效实用的途径。

> Machine unlearning aims to remove specific information, e.g. sensitive or undesirable content, from large language models (LLMs) while preserving overall performance. We propose an inference-time unlearning algorithm that uses contrastive decoding, leveraging two auxiliary smaller models, one trained without the forget set and one trained with it, to guide the outputs of the original model using their difference during inference. Our strategy substantially improves the tradeoff between unlearning effectiveness and model utility. We evaluate our approach on two unlearning benchmarks, TOFU and MUSE. Results show notable gains in both forget quality and retained performance in comparison to prior approaches, suggesting that incorporating contrastive decoding can offer an efficient, practical avenue for unlearning concepts in large-scale models.

[Arxiv](https://arxiv.org/abs/2506.12097)