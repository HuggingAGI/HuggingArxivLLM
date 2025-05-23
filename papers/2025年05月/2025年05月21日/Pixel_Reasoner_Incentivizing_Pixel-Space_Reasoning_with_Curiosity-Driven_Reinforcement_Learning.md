# Pixel Reasoner：利用好奇心驱动的强化学习激发像素空间推理能力

发布时间：2025年05月21日

`LLM应用` `视觉推理` `视觉语言模型`

> Pixel Reasoner: Incentivizing Pixel-Space Reasoning with Curiosity-Driven Reinforcement Learning

# 摘要

> 链式思维推理显著提升了大型语言模型 (LLMs) 在多个领域的性能。然而，这种推理过程仅限于文本空间，限制了其在视觉密集型任务中的有效性。为了解决这一限制，我们引入了像素空间推理的概念。在这个新颖的框架下，视觉语言模型 (VLMs) 配备了一系列视觉推理操作，如放大和选择帧。这些操作使 VLMs 能够直接检查、质询和从视觉证据中推断，从而提高视觉任务的推理保真度。在 VLMs 中培养这种像素空间推理能力面临显著挑战，包括模型初始能力的不平衡以及其不愿采用新引入的像素空间操作。我们通过两阶段训练方法解决这些挑战。第一阶段使用合成推理轨迹进行指令微调，使模型熟悉新型视觉操作。随后，强化学习 (RL) 阶段利用好奇心驱动的奖励方案，在像素空间推理和文本推理之间平衡探索。借助这些视觉操作，VLMs 可以与复杂视觉输入（如信息丰富的图像或视频）互动，主动收集必要信息。我们证明，这种方法显著提升了 VLM 在各种视觉推理基准上的性能。我们的 7B 模型，\model，在 V* bench 上达到 84%，TallyQA-Complex 上达到 74%，InfographicsVQA 上达到 84%，这是迄今为止开源模型取得的最高准确率。这些结果突显了像素空间推理的重要性以及我们框架的有效性。

> Chain-of-thought reasoning has significantly improved the performance of Large Language Models (LLMs) across various domains. However, this reasoning process has been confined exclusively to textual space, limiting its effectiveness in visually intensive tasks. To address this limitation, we introduce the concept of reasoning in the pixel-space. Within this novel framework, Vision-Language Models (VLMs) are equipped with a suite of visual reasoning operations, such as zoom-in and select-frame. These operations enable VLMs to directly inspect, interrogate, and infer from visual evidences, thereby enhancing reasoning fidelity for visual tasks. Cultivating such pixel-space reasoning capabilities in VLMs presents notable challenges, including the model's initially imbalanced competence and its reluctance to adopt the newly introduced pixel-space operations. We address these challenges through a two-phase training approach. The first phase employs instruction tuning on synthesized reasoning traces to familiarize the model with the novel visual operations. Following this, a reinforcement learning (RL) phase leverages a curiosity-driven reward scheme to balance exploration between pixel-space reasoning and textual reasoning. With these visual operations, VLMs can interact with complex visual inputs, such as information-rich images or videos to proactively gather necessary information. We demonstrate that this approach significantly improves VLM performance across diverse visual reasoning benchmarks. Our 7B model, \model, achieves 84\% on V* bench, 74\% on TallyQA-Complex, and 84\% on InfographicsVQA, marking the highest accuracy achieved by any open-source model to date. These results highlight the importance of pixel-space reasoning and the effectiveness of our framework.

[Arxiv](https://arxiv.org/abs/2505.15966)