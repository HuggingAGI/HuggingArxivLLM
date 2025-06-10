# 多步骤视觉推理：视觉标记的扩展与验证

发布时间：2025年06月08日

`LLM应用` `多模态` `视觉推理`

> Multi-Step Visual Reasoning with Visual Tokens Scaling and Verification

# 摘要

> 多模态大语言模型（MLLMs）通过结合视觉感知与语言理解，展现出强大的能力，支持图像对话、视觉问答和科学分析等应用。然而，现有MLLMs大多采用静态推理方式，在推理前将整张图像编码为固定视觉令牌，限制了其在推理过程中逐步优化理解或适应上下文的能力。这与人类动态、选择性和反馈驱动的感知方式形成鲜明对比。本研究提出了一种全新的推理时视觉令牌缩放框架，使MLLMs能够进行迭代、基于验证器引导的视觉推理。我们将其建模为马尔可夫决策过程，其中推理器提出视觉动作，验证器通过多步直接偏好优化（DPO）训练，评估动作并决定推理终止时机。为此，我们构建了新的VTS数据集，包含监督推理轨迹（VTS-SFT）和偏好标注推理比较（VTS-DPO）。实验结果表明，我们的方法在多种视觉推理基准测试中显著优于现有方法，不仅提升了准确性，还带来了更可解释和基于上下文的推理过程。这证明了动态推理机制在实现下一代MLLMs精细、上下文感知视觉推理方面的巨大潜力。

> Multi-modal large language models (MLLMs) have achieved remarkable capabilities by integrating visual perception with language understanding, enabling applications such as image-grounded dialogue, visual question answering, and scientific analysis. However, most MLLMs adopt a static inference paradigm, encoding the entire image into fixed visual tokens upfront, which limits their ability to iteratively refine understanding or adapt to context during inference. This contrasts sharply with human perception, which is dynamic, selective, and feedback-driven. In this work, we introduce a novel framework for inference-time visual token scaling that enables MLLMs to perform iterative, verifier-guided reasoning over visual content. We formulate the problem as a Markov Decision Process, involving a reasoner that proposes visual actions and a verifier, which is trained via multi-step Direct Preference Optimization (DPO), that evaluates these actions and determines when reasoning should terminate. To support this, we present a new dataset, VTS, comprising supervised reasoning trajectories (VTS-SFT) and preference-labeled reasoning comparisons (VTS-DPO). Our method significantly outperforms existing approaches across diverse visual reasoning benchmarks, offering not only improved accuracy but also more interpretable and grounded reasoning processes. These results demonstrate the promise of dynamic inference mechanisms for enabling fine-grained, context-aware visual reasoning in next-generation MLLMs.

[Arxiv](https://arxiv.org/abs/2506.07235)