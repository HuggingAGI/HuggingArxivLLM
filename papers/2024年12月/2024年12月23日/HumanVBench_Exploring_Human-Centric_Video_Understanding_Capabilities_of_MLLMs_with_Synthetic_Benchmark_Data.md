# HumanVBench：借助合成基准数据探索 MLLMs 以人为本的视频理解能力

发布时间：2024年12月23日

`LLM应用` `多模态`

> HumanVBench: Exploring Human-Centric Video Understanding Capabilities of MLLMs with Synthetic Benchmark Data

# 摘要

> 在多模态大型语言模型（MLLMs）的范畴中，达成以人为本的视频理解依旧是个巨大的挑战。现有的基准重点多在对象和动作识别上，常常忽略了视频内容里人类情感、行为以及言语视觉对齐的复杂细微之处。我们推出了 HumanVBench，这是一个精心打造的创新基准，旨在填补视频 MLLMs 评估中的这些空缺。HumanVBench 涵盖 17 个精心规划的任务，探索了两个主要维度：内在情感和外在表现，包含静态与动态、基础与复杂，以及单模态和跨模态等方面。凭借两个用于视频标注和包含干扰项的 QA 生成的先进自动化流程，HumanVBench 运用多种最先进（SOTA）的技术来优化基准数据合成和质量评估，最大程度减少针对以人为本的多模态属性的人工标注依赖。对 16 个 SOTA 视频 MLLMs 的全面评估揭示了当前性能的显著局限，特别是在跨模态和时间对齐方面，凸显了为实现更类人的理解而进一步改进的必要性。HumanVBench 开源，以助力视频 MLLMs 的未来进步和实际应用。

> In the domain of Multimodal Large Language Models (MLLMs), achieving human-centric video understanding remains a formidable challenge. Existing benchmarks primarily emphasize object and action recognition, often neglecting the intricate nuances of human emotions, behaviors, and speech visual alignment within video content. We present HumanVBench, an innovative benchmark meticulously crafted to bridge these gaps in the evaluation of video MLLMs. HumanVBench comprises 17 carefully designed tasks that explore two primary dimensions: inner emotion and outer manifestations, spanning static and dynamic, basic and complex, as well as single-modal and cross-modal aspects. With two advanced automated pipelines for video annotation and distractor-included QA generation, HumanVBench utilizes diverse state-of-the-art (SOTA) techniques to streamline benchmark data synthesis and quality assessment, minimizing human annotation dependency tailored to human-centric multimodal attributes. A comprehensive evaluation across 16 SOTA video MLLMs reveals notable limitations in current performance, especially in cross-modal and temporal alignment, underscoring the necessity for further refinement toward achieving more human-like understanding. HumanVBench is open-sourced to facilitate future advancements and real-world applications in video MLLMs.

[Arxiv](https://arxiv.org/abs/2412.17574)