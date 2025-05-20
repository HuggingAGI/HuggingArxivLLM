# ExTrans：基于示例增强的强化学习实现多语言深度推理翻译

发布时间：2025年05月19日

`LLM应用

摘要中的论文主要探讨了将大型推理模型（LRMs）应用于神经机器翻译（MT）领域，并提出了一种新的奖励建模方法来提升翻译性能。虽然提到了强化学习（RL），但研究的核心是将LRMs应用于MT任务，并展示了其在多语言场景中的有效性。因此，这属于LLM应用类别。` `神经机器翻译`

> ExTrans: Multilingual Deep Reasoning Translation via Exemplar-Enhanced Reinforcement Learning

# 摘要

> 近年来，大型推理模型（LRMs）如 OpenAI-o1 和 DeepSeek-R1 崭露头角，在数学和编程等复杂问题领域展现出了非凡的潜力。研究者们尝试将这些模型的成功经验引入神经机器翻译（MT）领域，通过强化学习（RL）构建具有深度推理能力的 MT 模型。然而，尽管取得了一定进展，现有研究主要集中在英语和中文等高资源语言上，对其他语言的效果尚不明确。此外，传统的奖励建模方法未能充分挖掘强化学习在 MT 中的潜力。

在本研究中，我们提出了一种全新的奖励建模方法。该方法将策略 MT 模型的翻译结果与强大的 LRM（即 DeepSeek-R1-671B）进行对比，并通过量化比较结果提供奖励信号。实验结果证明，这种奖励建模方法具有显著优势。基于 Qwen2.5-7B-Instruct 模型，我们的训练模型在文学翻译领域达到了新的最佳性能水平，超越了 OpenAI-o1 和 DeepSeek-R1 等强大 LRM。此外，我们将方法扩展至包含 11 种语言的多语言场景。借助轻量级奖励建模方法，在强化学习框架下，我们成功将强大的 MT 能力从单一方向扩展至 90 个翻译方向，实现了令人瞩目的多语言 MT 性能。

> In recent years, the emergence of large reasoning models (LRMs), such as OpenAI-o1 and DeepSeek-R1, has shown impressive capabilities in complex problems, e.g., mathematics and coding. Some pioneering studies attempt to bring the success of LRMs in neural machine translation (MT). They try to build LRMs with deep reasoning MT ability via reinforcement learning (RL). Despite some progress that has been made, these attempts generally focus on several high-resource languages, e.g., English and Chinese, leaving the performance on other languages unclear. Besides, the reward modeling methods in previous work do not fully unleash the potential of reinforcement learning in MT. In this work, we first design a new reward modeling method that compares the translation results of the policy MT model with a strong LRM (i.e., DeepSeek-R1-671B), and quantifies the comparisons to provide rewards. Experimental results demonstrate the superiority of the reward modeling method. Using Qwen2.5-7B-Instruct as the backbone, the trained model achieves the new state-of-the-art performance in literary translation, and outperforms strong LRMs including OpenAI-o1 and DeepSeeK-R1. Furthermore, we extend our method to the multilingual settings with 11 languages. With a carefully designed lightweight reward modeling in RL, we can simply transfer the strong MT ability from a single direction into multiple (i.e., 90) translation directions and achieve impressive multilingual MT performance.

[Arxiv](https://arxiv.org/abs/2505.12996)