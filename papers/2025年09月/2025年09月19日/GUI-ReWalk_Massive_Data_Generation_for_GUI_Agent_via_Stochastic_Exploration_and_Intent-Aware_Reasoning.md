# GUI-ReWalk：基于随机探索与意图感知推理的GUI智能体大规模数据生成

发布时间：2025年09月19日

`Agent` `基础理论`

> GUI-ReWalk: Massive Data Generation for GUI Agent via Stochastic Exploration and Intent-Aware Reasoning

# 摘要

> 图形用户界面（GUI）智能体借助大型语言模型与视觉-语言模型的驱动，有望在数字环境中实现端到端自动化。然而，其发展从根本上受限于可扩展、高质量轨迹数据的稀缺。现有数据收集策略要么依赖成本高昂且质量参差不齐的人工标注，要么依赖在多样性与有意义任务覆盖之间权衡的合成生成方法。为填补这一空白，我们提出GUI-ReWalk：一种推理增强的多阶段框架，用于合成真实且多样的GUI轨迹。该框架先通过随机探索阶段模拟人类试错行为，再逐步过渡到推理引导阶段，由推断目标驱动连贯且有目的的交互。此外，它支持多步骤任务生成，可构建跨多个应用的长程工作流。通过将用于多样性的随机性与用于结构化的目标感知推理相结合，GUI-ReWalk生成的数据更准确地反映了人机交互中意图感知、自适应的本质。我们进一步在GUI-ReWalk数据集上训练了Qwen2.5-VL-7B，并在Screenspot-Pro、OSWorld-G、UI-Vision、AndroidControl及GUI-Odyssey等多个基准上进行评估。结果显示，GUI-ReWalk实现了更优的多样化交互流程覆盖、更高的轨迹熵以及更真实的用户意图。这些发现表明，GUI-ReWalk是推动GUI智能体研究并实现稳健的现实世界自动化的可扩展且数据高效的框架。

> Graphical User Interface (GUI) Agents, powered by large language and vision-language models, hold promise for enabling end-to-end automation in digital environments. However, their progress is fundamentally constrained by the scarcity of scalable, high-quality trajectory data. Existing data collection strategies either rely on costly and inconsistent manual annotations or on synthetic generation methods that trade off between diversity and meaningful task coverage. To bridge this gap, we present GUI-ReWalk: a reasoning-enhanced, multi-stage framework for synthesizing realistic and diverse GUI trajectories. GUI-ReWalk begins with a stochastic exploration phase that emulates human trial-and-error behaviors, and progressively transitions into a reasoning-guided phase where inferred goals drive coherent and purposeful interactions. Moreover, it supports multi-stride task generation, enabling the construction of long-horizon workflows across multiple applications. By combining randomness for diversity with goal-aware reasoning for structure, GUI-ReWalk produces data that better reflects the intent-aware, adaptive nature of human-computer interaction. We further train Qwen2.5-VL-7B on the GUI-ReWalk dataset and evaluate it across multiple benchmarks, including Screenspot-Pro, OSWorld-G, UI-Vision, AndroidControl, and GUI-Odyssey. Results demonstrate that GUI-ReWalk enables superior coverage of diverse interaction flows, higher trajectory entropy, and more realistic user intent. These findings establish GUI-ReWalk as a scalable and data-efficient framework for advancing GUI agent research and enabling robust real-world automation.

[Arxiv](https://arxiv.org/abs/2509.15738)