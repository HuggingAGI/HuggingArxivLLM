# 赋能大型语言模型在任务导向对话中：一个领域无关的多智能体框架及微调策略

发布时间：2025年05月20日

`LLM应用` `任务导向对话系统` `对话系统`

> Empowering LLMs in Task-Oriented Dialogues: A Domain-Independent Multi-Agent Framework and Fine-Tuning Strategy

# 摘要

> 基于大型语言模型 (LLMs) 的任务导向对话系统在多个行业领域中备受关注，并取得了显著成果。当前方法通过将复杂的程序工作流浓缩到单一智能体中，在大规模 LLM 上实现了令人满意的性能。然而，这些方法在针对轻量化 LLM 的微调过程中面临挑战，因为它们在处理多复杂逻辑方面的能力有限。

在本研究中，我们设计了一个领域无关多智能体框架 (DIMF)，包含意图分类智能体、槽填充智能体和响应智能体。通过将任务分解为领域无关的组件，此方法不仅简化了学习复杂度，还显著提升了模型的泛化能力。在此框架中，我们采用直接偏好优化 (DPO) 方法增强上下文理解能力，并提出了一种简单有效的数据分布适应 (DDA) 方法，以缓解 DPO 训练过程中的性能下降问题。

在 MultiWOZ 数据集上的实验表明，我们的方法在所有基线模型中实现了更好的平均性能。详细分析还表明，我们的框架展现了卓越的泛化能力和零样本学习能力。

> Task-oriented dialogue systems based on Large Language Models (LLMs) have gained increasing attention across various industries and achieved significant results. Current approaches condense complex procedural workflows into a single agent to achieve satisfactory performance on large-scale LLMs. However, these approaches face challenges to achieve comparable performance on fine-tuned lightweight LLMs, due to their limited capabilities in handling multiple complex logic. In this work, we design a Domain-Independent Multi-Agent Framework (DIMF), which contains Intent Classification Agent, Slot Filling Agent and Response Agent. This approach simplifies the learning complexity and enhances the generalization ability by separating the tasks into domain-independent components. In this framework, we enhance the capabilities in contextual understanding using the Direct Preference Optimisation (DPO) method, and propose a simple and effective Data Distribution Adaptation (DDA) method to mitigate degradation issues during DPO training. Experiments conducted on the MultiWOZ datasets show that our proposed method achieves a better average performance among all the baselines. Extensive analysis also demonstrates that our proposed framework exhibits excellent generalizability and zero-shot capability.

[Arxiv](https://arxiv.org/abs/2505.14299)