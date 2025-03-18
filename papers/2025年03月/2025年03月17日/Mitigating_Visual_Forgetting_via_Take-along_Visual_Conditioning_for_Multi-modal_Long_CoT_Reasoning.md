# 伴随视觉条件缓解视觉遗忘，实现多模态长链推理

发布时间：2025年03月17日

`LLM应用` `多模态` `数学推理`

> Mitigating Visual Forgetting via Take-along Visual Conditioning for Multi-modal Long CoT Reasoning

# 摘要

> 大型语言模型（LLMs）的最新进展展示了增强的推理能力，从链式思维（CoT）提示发展到先进的、面向产品的解决方案，如 OpenAI o1。在我们对这个模型的重新实现过程中，我们发现，在需要视觉输入的多模态任务（例如几何问题）中，多模态 LLMs（MLLMs）难以保持对视觉信息的关注，换句话说，随着推理的进行，MLLMs 对视觉信息的注意力逐渐下降，导致过度依赖文本的输出。为了研究这一现象，我们在长链推理过程中去除图像输入。具体来说，我们在推理过程中途截断推理过程，然后在移除输入图像的情况下重新完成推理过程。我们发现，在 MathVista 的 test-hard 子集上，准确率仅下降约 2%，这表明模型的文本输出主导了后续的推理过程。受到这一发现的启发，我们提出了随行视觉条件（TVC），这是一种将图像输入转移到关键推理阶段，并通过动态剪枝压缩冗余视觉标记的策略。该方法有助于模型在整个推理过程中保持对视觉组件的关注。我们的方法在五个数学推理基准测试中平均达到了最先进的性能（比之前的 SOTA 高 3.4%），证明了 TVC 在增强多模态推理系统中的有效性。

> Recent advancements in Large Language Models (LLMs) have demonstrated enhanced reasoning capabilities, evolving from Chain-of-Thought (CoT) prompting to advanced, product-oriented solutions like OpenAI o1. During our re-implementation of this model, we noticed that in multimodal tasks requiring visual input (e.g., geometry problems), Multimodal LLMs (MLLMs) struggle to maintain focus on the visual information, in other words, MLLMs suffer from a gradual decline in attention to visual information as reasoning progresses, causing text-over-relied outputs. To investigate this, we ablate image inputs during long-chain reasoning. Concretely, we truncate the reasoning process midway, then re-complete the reasoning process with the input image removed. We observe only a ~2% accuracy drop on MathVista's test-hard subset, revealing the model's textual outputs dominate the following reasoning process. Motivated by this, we propose Take-along Visual Conditioning (TVC), a strategy that shifts image input to critical reasoning stages and compresses redundant visual tokens via dynamic pruning. This methodology helps the model retain attention to the visual components throughout the reasoning. Our approach achieves state-of-the-art performance on average across five mathematical reasoning benchmarks (+3.4% vs previous sota), demonstrating the effectiveness of TVC in enhancing multimodal reasoning systems.

[Arxiv](https://arxiv.org/abs/2503.13360)