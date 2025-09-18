# LLM-I：大型语言模型（LLMs）天然是交织的多模态创作者

发布时间：2025年09月16日

`Agent` `媒体与娱乐`

> LLM-I: LLMs are Naturally Interleaved Multimodal Creators

# 摘要

> 我们提出了LLM-Interleaved（LLM-I）——一个灵活且动态的框架，它将交错图文生成重新定义为工具使用问题。LLM-I旨在突破当前统一模型的“单一工具”瓶颈：这些模型往往局限于合成图像生成，在需要事实依据或程序精度的任务中难以胜任。我们的框架让中央LLM或MLLM智能体能够智能调度多样化的专业视觉工具集，包括在线图像搜索、扩散生成、代码执行和图像编辑等。该智能体通过强化学习（RL）框架训练，能够熟练选择和应用这些工具。该框架采用混合奖励系统，融合了基于规则的逻辑与LLM及MLLM评估器的判断。LLM-I在多样化的新数据集上使用四种不同的模型骨干进行训练，在四个基准测试中均展现出最先进的性能，大幅超越现有方法。我们还提出了一种新颖的测试时扩展策略，进一步提升了性能。项目页面：https://github.com/ByteDance-BandAI/LLM-I。

> We propose LLM-Interleaved (LLM-I), a flexible and dynamic framework that reframes interleaved image-text generation as a tool-use problem. LLM-I is designed to overcome the "one-tool" bottleneck of current unified models, which are limited to synthetic imagery and struggle with tasks requiring factual grounding or programmatic precision. Our framework empowers a central LLM or MLLM agent to intelligently orchestrate a diverse toolkit of specialized visual tools, including online image search, diffusion-based generation, code execution, and image editing. The agent is trained to select and apply these tools proficiently via a Reinforcement Learning (RL) framework that features a hybrid reward system combining rule-based logic with judgments from LLM and MLLM evaluators. Trained on a diverse new dataset using four different model backbones, LLM-I demonstrates state-of-the-art performance, outperforming existing methods by a large margin across four benchmarks. We also introduce a novel test-time scaling strategy that provides further performance gains. Project Page: https://github.com/ByteDance-BandAI/LLM-I.

[Arxiv](https://arxiv.org/abs/2509.13642)