# 深入研究：大型语言模型的推理能力解析

发布时间：2025年02月28日

`LLM理论` `模型优化`

> LLM Post-Training: A Deep Dive into Reasoning Large Language Models

# 摘要

> 大型语言模型（LLMs）彻底改变了自然语言处理领域，催生了众多创新应用。预训练基于海量网络数据，为这些模型奠定了基础，但研究界正转向后训练技术寻求进一步突破。预训练提供了语言基础，而后训练技术则帮助LLMs精炼知识、提升推理、增强事实准确性，并更好地适应用户意图与伦理考量。微调、强化学习和推理扩展成为优化LLMs性能、确保稳健性及提升适应性的关键策略。本研究系统探讨了后训练方法，分析其在预训练基础上精炼模型的作用，并针对灾难性遗忘、奖励操控和推理权衡等挑战展开讨论。我们聚焦于模型对齐、可扩展适应和推理推理等新兴方向，并规划未来研究路径。同时，我们提供了一个公共存储库，持续跟踪该快速发展的领域：https://github.com/mbzuai-oryx/Awesome-LLM-Post-training.

> Large Language Models (LLMs) have transformed the natural language processing landscape and brought to life diverse applications. Pretraining on vast web-scale data has laid the foundation for these models, yet the research community is now increasingly shifting focus toward post-training techniques to achieve further breakthroughs. While pretraining provides a broad linguistic foundation, post-training methods enable LLMs to refine their knowledge, improve reasoning, enhance factual accuracy, and align more effectively with user intents and ethical considerations. Fine-tuning, reinforcement learning, and test-time scaling have emerged as critical strategies for optimizing LLMs performance, ensuring robustness, and improving adaptability across various real-world tasks. This survey provides a systematic exploration of post-training methodologies, analyzing their role in refining LLMs beyond pretraining, addressing key challenges such as catastrophic forgetting, reward hacking, and inference-time trade-offs. We highlight emerging directions in model alignment, scalable adaptation, and inference-time reasoning, and outline future research directions. We also provide a public repository to continually track developments in this fast-evolving field: https://github.com/mbzuai-oryx/Awesome-LLM-Post-training.

[Arxiv](https://arxiv.org/abs/2502.21321)