# ThinkFake：多模态大型语言模型推理助力AI生成图像检测

发布时间：2025年09月24日

`LLM应用` `媒体与娱乐`

> ThinkFake: Reasoning in Multimodal Large Language Models for AI-Generated Image Detection

# 摘要

> AI生成图像的真实感日益增强，引发了对虚假信息传播和隐私侵犯的严重担忧，凸显了对准确且可解释的检测方法的迫切需求。尽管现有方法取得了进展，但多数要么依赖无解释的二分类，要么过度依赖监督微调，导致泛化能力受限。本文提出ThinkFake——一个基于推理、具备泛化能力的新型AI生成图像检测框架。该方法利用配备伪造推理提示的多模态大型语言模型（MLLM），并通过精心设计奖励函数的组相对策略优化（GRPO）强化学习进行训练。这种设计使模型能够进行逐步推理，生成可解释的结构化输出。我们进一步引入结构化检测流水线，以提升推理质量和适应性。大量实验表明，ThinkFake在GenImage基准测试上性能优于现有最先进方法，并在极具挑战性的LOKI基准测试上展现出强大的零样本泛化能力。这些结果验证了该框架的有效性和鲁棒性。代码将在论文接收后发布。

> The increasing realism of AI-generated images has raised serious concerns about misinformation and privacy violations, highlighting the urgent need for accurate and interpretable detection methods. While existing approaches have made progress, most rely on binary classification without explanations or depend heavily on supervised fine-tuning, resulting in limited generalization. In this paper, we propose ThinkFake, a novel reasoning-based and generalizable framework for AI-generated image detection. Our method leverages a Multimodal Large Language Model (MLLM) equipped with a forgery reasoning prompt and is trained using Group Relative Policy Optimization (GRPO) reinforcement learning with carefully designed reward functions. This design enables the model to perform step-by-step reasoning and produce interpretable, structured outputs. We further introduce a structured detection pipeline to enhance reasoning quality and adaptability. Extensive experiments show that ThinkFake outperforms state-of-the-art methods on the GenImage benchmark and demonstrates strong zero-shot generalization on the challenging LOKI benchmark. These results validate our framework's effectiveness and robustness. Code will be released upon acceptance.

[Arxiv](https://arxiv.org/abs/2509.19841)