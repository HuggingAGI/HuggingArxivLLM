# SAE-SSV：基于稀疏表示空间的有监督引导，实现可靠的语言模型控制

发布时间：2025年05月21日

`LLM应用

摘要分析：这篇论文探讨了如何通过监督引导方法来控制大型语言模型的行为，属于应用层面的研究。作者提出的方法用于引导生成任务，如情感和真实度，因此归类为LLM应用。` `内容审核` `信息过滤`

> SAE-SSV: Supervised Steering in Sparse Representation Spaces for Reliable Control of Language Models

# 摘要

> 大型语言模型（LLMs）在自然语言理解和生成方面表现出色，但如何可靠地控制其行为仍具挑战性，特别是在开放生成场景中。本文提出了一种新颖的监督引导方法，该方法在稀疏、可解释的表示空间中运行。我们利用稀疏自动编码器（SAEs）获取稀疏潜在表示，旨在从模型激活中分离语义属性。接着，我们训练线性分类器来识别潜在表示中与任务相关的维度子空间。最后，我们在该子空间内学习受监督的引导向量，并对其进行优化，使其与目标行为对齐。在多个LLMs上进行的 sentiment、truthfulness 和 politics polarity 引导任务的实验表明，与现有方法相比，我们的监督引导向量在生成质量仅轻微下降的情况下，实现了更高的成功率。进一步分析发现，一个显著较小的子空间就足以实现有效的引导，从而实现更具体和可解释的干预。

> Large language models (LLMs) have demonstrated impressive capabilities in natural language understanding and generation, but controlling their behavior reliably remains challenging, especially in open-ended generation settings. This paper introduces a novel supervised steering approach that operates in sparse, interpretable representation spaces. We employ sparse autoencoders (SAEs)to obtain sparse latent representations that aim to disentangle semantic attributes from model activations. Then we train linear classifiers to identify a small subspace of task-relevant dimensions in latent representations. Finally, we learn supervised steering vectors constrained to this subspace, optimized to align with target behaviors. Experiments across sentiment, truthfulness, and politics polarity steering tasks with multiple LLMs demonstrate that our supervised steering vectors achieve higher success rates with minimal degradation in generation quality compared to existing methods. Further analysis reveals that a notably small subspace is sufficient for effective steering, enabling more targeted and interpretable interventions.

[Arxiv](https://arxiv.org/abs/2505.16188)