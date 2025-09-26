# SceneWeaver：基于可扩展自反思智能体的一体化3D场景合成

发布时间：2025年09月24日

`Agent` `媒体与娱乐`

> SceneWeaver: All-in-One 3D Scene Synthesis with an Extensible and Self-Reflective Agent

# 摘要

> 随着具身智能（Embodied AI）的崛起，室内场景合成的重要性日益凸显——所需的3D环境不仅要视觉逼真，还得物理合理、功能多样。尽管近年方法在视觉保真度上取得进展，但它们常受限于固定场景类别，缺乏足够的物体级细节与物理一致性，且难以匹配复杂的用户指令。为此，我们提出SceneWeaver——一个反思型智能体框架，通过工具化迭代优化来统一多样的场景合成范式。其核心在于：借助基于语言模型的规划器，从一套可扩展场景生成工具（涵盖数据驱动生成模型、视觉方法及LLM方法等）中择取合适工具，并通过自我评估（物理合理性、视觉真实感及与用户输入的语义匹配度）进行引导。这种“推理-行动-反思”的闭环设计，让智能体能够识别语义矛盾、调用针对性工具，并在迭代中持续更新环境。在常见及开放词汇房间类型上的大量实验显示，SceneWeaver不仅在物理、视觉和语义指标上超越现有方法，还能有效泛化到含多样指令的复杂场景，为通用3D环境生成奠定了基础。项目网站：https://scene-weaver.github.io/。

> Indoor scene synthesis has become increasingly important with the rise of Embodied AI, which requires 3D environments that are not only visually realistic but also physically plausible and functionally diverse. While recent approaches have advanced visual fidelity, they often remain constrained to fixed scene categories, lack sufficient object-level detail and physical consistency, and struggle to align with complex user instructions. In this work, we present SceneWeaver, a reflective agentic framework that unifies diverse scene synthesis paradigms through tool-based iterative refinement. At its core, SceneWeaver employs a language model-based planner to select from a suite of extensible scene generation tools, ranging from data-driven generative models to visual- and LLM-based methods, guided by self-evaluation of physical plausibility, visual realism, and semantic alignment with user input. This closed-loop reason-act-reflect design enables the agent to identify semantic inconsistencies, invoke targeted tools, and update the environment over successive iterations. Extensive experiments on both common and open-vocabulary room types demonstrate that SceneWeaver not only outperforms prior methods on physical, visual, and semantic metrics, but also generalizes effectively to complex scenes with diverse instructions, marking a step toward general-purpose 3D environment generation. Project website: https://scene-weaver.github.io/.

[Arxiv](https://arxiv.org/abs/2509.20414)