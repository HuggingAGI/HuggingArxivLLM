# GUI-Reflection：赋予多模态 GUI 模型自我反思能力

发布时间：2025年06月09日

`LLM应用` `软件工程` `人工智能`

> GUI-Reflection: Empowering Multimodal GUI Models with Self-Reflection Behavior

# 摘要

> 多模态大型语言模型（MLLMs）在图形用户界面（GUI）自动化的变革中展现出巨大潜力。然而，现有的GUI模型主要依赖几乎无错误的离线轨迹进行学习，缺乏反思与错误恢复能力。为解决这一问题，我们提出了GUI-Reflection框架，通过专门的训练阶段（包括GUI特定预训练、离线监督微调（SFT）和在线反思调优）将自我反思和错误纠正能力集成到端到端多模态GUI模型中。GUI-Reflection通过完全自动化数据生成与学习过程实现了自我反思行为的出现，无需人工标注。具体而言，1) 我们提出了可扩展的数据管道，能够从现有成功轨迹中自动构建反思与错误纠正数据。现有GUI模型主要关注接地与UI理解能力，而我们提出了GUI-Reflection任务套件，显式学习和评估反思导向能力。2) 此外，我们构建了一个多样化且高效的环境，用于移动设备上GUI模型的在线训练与数据收集。3) 我们还提出了一种迭代在线反思调优算法，利用所构建环境，使模型能够持续提升反思与错误纠正能力。我们的框架为GUI代理赋予了自我反思与纠正能力，为更强大、灵活和智能的GUI自动化铺平了道路。所有数据、模型、环境和工具都将公开发布。

> Multimodal Large Language Models (MLLMs) have shown great potential in revolutionizing Graphical User Interface (GUI) automation. However, existing GUI models mostly rely on learning from nearly error-free offline trajectories, thus lacking reflection and error recovery capabilities. To bridge this gap, we propose GUI-Reflection, a novel framework that explicitly integrates self-reflection and error correction capabilities into end-to-end multimodal GUI models throughout dedicated training stages: GUI-specific pre-training, offline supervised fine-tuning (SFT), and online reflection tuning. GUI-reflection enables self-reflection behavior emergence with fully automated data generation and learning processes without requiring any human annotation. Specifically, 1) we first propose scalable data pipelines to automatically construct reflection and error correction data from existing successful trajectories. While existing GUI models mainly focus on grounding and UI understanding ability, we propose the GUI-Reflection Task Suite to learn and evaluate reflection-oriented abilities explicitly. 2) Furthermore, we built a diverse and efficient environment for online training and data collection of GUI models on mobile devices. 3) We also present an iterative online reflection tuning algorithm leveraging the proposed environment, enabling the model to continuously enhance its reflection and error correction abilities. Our framework equips GUI agents with self-reflection and correction capabilities, paving the way for more robust, adaptable, and intelligent GUI automation, with all data, models, environments, and tools to be released publicly.

[Arxiv](https://arxiv.org/abs/2506.08012)