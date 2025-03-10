# # R1-Zero在20亿参数非SFT模型中实现视觉推理的突破

发布时间：2025年03月06日

`LLM应用

摘要主要讨论了强化学习在大型语言模型中的应用，特别是如何通过结合基于规则的激励来实现复杂推理能力的自主发展，并展示了在多模态推理中的应用和结果。这些内容属于LLM的应用领域。` `人工智能` `计算机视觉`

> R1-Zero's "Aha Moment" in Visual Reasoning on a 2B Non-SFT Model

# 摘要

> 最近，DeepSeek R1展示了强化学习结合简单的基于规则激励如何能够实现大型语言模型中复杂推理能力的自主发展，这一过程以“顿悟时刻”为特征，即模型在训练过程中表现出自我反思，并增加响应长度。然而，将这一成功扩展到多模态推理时，往往无法再现这些关键特征。在这份报告中，我们首次成功地在一个非SFT的20亿参数模型上复现了这些涌现特性。从Qwen2-VL-2B出发，并直接在SAT数据集上应用强化学习，我们的模型在CVBench上实现了59.47%的准确率，比基础模型高出约30%，并在两种SFT设置中分别超出约2%。此外，我们还分享了我们在尝试使用强化学习与指令模型实现类似R1推理过程中的失败尝试和见解，旨在揭示其中的挑战。我们的主要观察包括：(1) 在指令模型上应用强化学习往往导致简单的推理轨迹，以及(2) 直接的长度奖励无法有效激发推理能力。项目代码可在https://github.com/turningpoint-ai/VisualThinker-R1-Zero获取。

> Recently DeepSeek R1 demonstrated how reinforcement learning with simple rule-based incentives can enable autonomous development of complex reasoning in large language models, characterized by the "aha moment", in which the model manifest self-reflection and increased response length during training. However, attempts to extend this success to multimodal reasoning often failed to reproduce these key characteristics. In this report, we present the first successful replication of these emergent characteristics for multimodal reasoning on only a non-SFT 2B model. Starting with Qwen2-VL-2B and applying reinforcement learning directly on the SAT dataset, our model achieves 59.47% accuracy on CVBench, outperforming the base model by approximately ~30% and exceeding both SFT setting by ~2%. In addition, we share our failed attempts and insights in attempting to achieve R1-like reasoning using RL with instruct models. aiming to shed light on the challenges involved. Our key observations include: (1) applying RL on instruct model often results in trivial reasoning trajectories, and (2) naive length reward are ineffective in eliciting reasoning capabilities. The project code is available at https://github.com/turningpoint-ai/VisualThinker-R1-Zero

[Arxiv](https://arxiv.org/abs/2503.05132)