# 情绪理解的自适应长程推理：LLMs中的情感-o1

发布时间：2025年05月28日

`LLM应用

摘要讨论了情感理解任务，并提出了一种任务自适应推理框架，利用LLMs进行情感分析和高级任务处理，属于LLM的应用领域。` `情感分析`

> Emotion-o1: Adaptive Long Reasoning for Emotion Understanding in LLMs

# 摘要

> 情感理解涵盖基础任务（如情感/情绪分类）和高级任务（如讽刺/幽默检测）。现有方法采用固定长度的CoT推理，难以适应情感复杂性的变化。我们提出了一种任务自适应推理框架，利用DeepSeek-R1生成不同情感任务的可变长度推理链。通过结合微调与强化学习，我们设计了一个复合奖励函数，平衡了四个目标：预测准确性、自适应推理深度控制、推理路径的结构多样性以及重复逻辑的抑制。这种方法不仅实现了动态上下文敏感推理，还使LLMs能够自主发展深度推理能力。实验结果显示，在情感、情感分类、幽默和讽刺四项任务中，准确率（Acc）和F1分数均有显著提升。值得注意的是，基础任务的F1提升了3.56%（Acc提升2.76%），而高级任务的F1提升了37.95%（Acc提升23.14%）。我们的工作通过自适应深度分析，成功弥合了 rigid CoT推理与情感复杂性之间的鸿沟。

> Emotion understanding includes basic tasks (e.g., sentiment/emotion classification) and advanced tasks (e.g., sarcasm/humor detection). Current methods rely on fixed-length CoT reasoning, failing to adapt to the varying complexity of emotions. We propose a task-adaptive reasoning framework that employs DeepSeek-R1 to generate variable-length reasoning chains for different emotion tasks. By combining fine-tuning with reinforcement learning, we design a composite reward function that balances four objectives: prediction accuracy, adaptive reasoning depth control, structural diversity in reasoning paths, and suppression of repetitive logic. This approach achieves dynamic context-sensitive inference while enabling LLMs to autonomously develop deep reasoning capabilities. Experimental results demonstrate consistent improvements in both Acc and F1 scores across four tasks: emotion, sentiment, humor, and sarcasm. Notably, peak enhancements reached 3.56% F1 (2.76% Acc) for basic tasks and 37.95% F1 (23.14% Acc) for advanced tasks. Our work bridges rigid CoT reasoning and emotional complexity through adaptive-depth analysis.

[Arxiv](https://arxiv.org/abs/2505.22548)