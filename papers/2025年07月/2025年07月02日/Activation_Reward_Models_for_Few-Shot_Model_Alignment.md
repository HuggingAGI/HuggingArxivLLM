# 基于激活奖励的模型对齐方法在少样本场景中的应用

发布时间：2025年07月02日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）与人类偏好对齐的方法，特别是通过引入激活奖励模型（Activation RMs）来改进奖励建模。这属于模型训练和优化的理论层面，而非具体应用实例。因此，归类为LLM理论。` `模型对齐` `模型优化`

> Activation Reward Models for Few-Shot Model Alignment

# 摘要

> 将大型语言模型（LLMs）和大型多模态模型（LMMs）与人类偏好对齐，是提升模型生成输出质量以适应实际应用中的核心挑战。常用方法是通过奖励建模来编码偏好，从而利用强化学习在训练后进行对齐。然而，传统的奖励建模难以适应新偏好，因为它需要一个单独的奖励模型，通常基于大型偏好数据集进行训练。为解决这一问题，我们引入了激活奖励模型（Activation RMs）——一种新颖的少样本奖励建模方法，通过利用激活引导，仅需极小的监督即可构建良好的对齐奖励信号，且无需额外的模型微调。在标准的奖励建模基准测试中，Activation RMs超越了现有的少样本奖励建模方法，如基于上下文学习的LLM作为裁判、基于投票的评分和基于token概率的评分。此外，我们展示了Activation RMs在缓解奖励欺骗行为方面的有效性，突显了其在安全关键应用中的实用性。为此，我们提出了PreferenceHack，一个新颖的少样本设置基准，首次以配对偏好格式测试奖励模型的奖励欺骗能力。最后，我们展示了Activation RM在该基准上的最先进性能，甚至超越了GPT-4o。

> Aligning Large Language Models (LLMs) and Large Multimodal Models (LMMs) to human preferences is a central challenge in improving the quality of the models' generative outputs for real-world applications. A common approach is to use reward modeling to encode preferences, enabling alignment via post-training using reinforcement learning. However, traditional reward modeling is not easily adaptable to new preferences because it requires a separate reward model, commonly trained on large preference datasets. To address this, we introduce Activation Reward Models (Activation RMs) -- a novel few-shot reward modeling method that leverages activation steering to construct well-aligned reward signals using minimal supervision and no additional model finetuning. Activation RMs outperform existing few-shot reward modeling approaches such as LLM-as-a-judge with in-context learning, voting-based scoring, and token probability scoring on standard reward modeling benchmarks. Furthermore, we demonstrate the effectiveness of Activation RMs in mitigating reward hacking behaviors, highlighting their utility for safety-critical applications. Toward this end, we propose PreferenceHack, a novel few-shot setting benchmark, the first to test reward models on reward hacking in a paired preference format. Finally, we show that Activation RM achieves state-of-the-art performance on this benchmark, surpassing even GPT-4o.

[Arxiv](https://arxiv.org/abs/2507.01368)