# SILMM：用于组合式文本转图像生成的自我改进型大型多模态模型

发布时间：2024年12月08日

`LLM应用` `多模态` `图像生成`

> SILMM: Self-Improving Large Multimodal Models for Compositional Text-to-Image Generation

# 摘要

> 大型多模态模型（LMMs）在多模态理解与生成领域表现出色，有力推动了文本到图像生成技术的发展。但要为 LMMs 实现精准的文本 - 图像对齐，尤其在组合场景下，仍困难重重。现有的诸如多步生成的布局规划以及从人类或 AI 反馈中学习等方法，过度依赖提示工程、昂贵的人工标注和持续升级，限制了其灵活性和可扩展性。在本研究中，我们引入了一个模型无关的迭代式自我改进框架（SILMM），它能让 LMMs 提供有用且可扩展的自我反馈，并通过直接偏好优化（DPO）来优化文本 - 图像对齐。DPO 易于应用于使用离散视觉标记作为中间图像表示的 LMMs；但对于具有连续视觉特征的 LMMs 则不太适用，因为获取生成概率颇具挑战。为使 SILMM 适配具有连续特征的 LMMs，我们提出了一种多样性机制以获取多样的表示，以及基于核的连续 DPO 来实现对齐。在三个组合文本到图像生成基准上开展的大量实验，证实了 SILMM 的有效性和优越性，在 T2I-CompBench++ 上改进超过 30％，在 DPG-Bench 上约为 20％。

> Large Multimodal Models (LMMs) have demonstrated impressive capabilities in multimodal understanding and generation, pushing forward advancements in text-to-image generation. However, achieving accurate text-image alignment for LMMs, particularly in compositional scenarios, remains challenging. Existing approaches, such as layout planning for multi-step generation and learning from human feedback or AI feedback, depend heavily on prompt engineering, costly human annotations, and continual upgrading, limiting flexibility and scalability. In this work, we introduce a model-agnostic iterative self-improvement framework (SILMM) that can enable LMMs to provide helpful and scalable self-feedback and optimize text-image alignment via Direct Preference Optimization (DPO). DPO can readily applied to LMMs that use discrete visual tokens as intermediate image representations; while it is less suitable for LMMs with continuous visual features, as obtaining generation probabilities is challenging. To adapt SILMM to LMMs with continuous features, we propose a diversity mechanism to obtain diverse representations and a kernel-based continuous DPO for alignment. Extensive experiments on three compositional text-to-image generation benchmarks validate the effectiveness and superiority of SILMM, showing improvements exceeding 30% on T2I-CompBench++ and around 20% on DPG-Bench.

[Arxiv](https://arxiv.org/abs/2412.05818)