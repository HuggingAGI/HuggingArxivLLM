# 没有免费午餐：重新思考LLM推理中的内部反馈机制

发布时间：2025年06月20日

`LLM理论` `人工智能` `机器学习`

> No Free Lunch: Rethinking Internal Feedback for LLM Reasoning

# 摘要

> 强化学习作为一种强大的范式，已被证明能够有效提升大型语言模型（LLM）的推理能力。人类反馈强化学习（RLHF）和可验证奖励强化学习（RLVR）等方法已展现出强大的效果，但它们需要大量外部监督。我们研究了一种全新的方法类别——内部反馈强化学习（RLIF），这种方法仅依赖于模型内部生成的信号，而非外部奖励。具体而言，我们利用了无监督奖励代理，包括词元级别熵、轨迹级别熵和自我置信度。理论分析表明，这些内部目标在一定程度上是等价的，而实证评估则在具有挑战性的数学推理基准测试中验证了各种RLIF策略的表现。实验结果表明，RLIF能够在训练初期显著提升基础LLM的推理性能，甚至在某些任务上超越RLVR技术。然而，随着训练的深入，性能逐渐下降，甚至低于训练前的模型水平。此外，我们发现RLIF对指令微调模型的改进效果有限，这表明一旦LLM已经过指令微调，内部反馈的收益会逐渐减弱。我们进一步通过混合模型权重的方式分析了这一限制，并解释了RLIF训练行为背后的原因，为将内部反馈信号整合到LLM训练中提供了实用指导。我们希望对内部反馈的分析能够为LLM后训练提供更系统、更有效的策略。


> Reinforcement learning has emerged as a powerful paradigm for post-training large language models (LLMs) to improve reasoning. Approaches like Reinforcement Learning from Human Feedback (RLHF) and Reinforcement Learning with Verifiable Rewards (RLVR) have shown strong results, but they require extensive external supervision. We investigate an alternative class of methods, Reinforcement Learning from Internal Feedback (RLIF), which relies solely on intrinsic model-derived signals instead of external rewards. In particular, we leverage unsupervised reward proxies such as token-level entropy, trajectory-level entropy, and self-certainty. Our theoretical analysis shows these internal objectives are partially equivalent, and we empirically evaluate various RLIF strategies on challenging math reasoning benchmarks. Experimental results demonstrate that RLIF can boost the reasoning performance of base LLMs at the beginning phase of the training, matching or surpassing RLVR techniques on these tasks. However, when training progresses, performance degrades even below the model before training. Moreover, we find that RLIF yields little improvement for instruction-tuned models, indicating diminishing returns of intrinsic feedback once an LLM is already instruction-tuned. We further analyze this limitation by mixing model weights and explain the reason of RLIF's training behaviors, providing practical guidelines for integrating internal feedback signals into LLM training. We hope our analysis of internal feedback will inform more principled and effective strategies for LLM post-training.

[Arxiv](https://arxiv.org/abs/2506.17219)