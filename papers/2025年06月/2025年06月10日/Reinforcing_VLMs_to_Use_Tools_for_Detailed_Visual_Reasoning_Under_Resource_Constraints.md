# 强化视觉语言模型在资源受限条件下使用工具进行详细视觉推理

发布时间：2025年06月10日

`LLM应用` `计算机视觉` `人工智能`

> Reinforcing VLMs to Use Tools for Detailed Visual Reasoning Under Resource Constraints

# 摘要

> 尽管近期在大型模型推理能力方面取得了显著进展，视觉语言模型（VLMs）在详细视觉推理方面仍然面临挑战，特别是在计算资源有限的情况下。为了解决这一问题，我们借鉴了Deepseek-r1等方法，针对VLMs使用组相对策略优化（GRPO）训练小规模模型，并结合外部工具如缩放功能。通过结合GRPO学习、简单奖励结构、简化的工具调用界面、为工具调用结果分配额外令牌以及包含更多视觉难题的训练数据集，我们获得了最大的收益。与同规模的基线模型相比，我们的方法在一些视觉问答任务（VQA）上取得了更好的表现，这得益于从外部工具获取的详细视觉信息。

> Despite tremendous recent advances in large model reasoning ability, vision-language models (VLMs) still struggle with detailed visual reasoning, especially when compute resources are limited. To address this challenge, we draw inspiration from methods like Deepseek-r1 for VLMs and train smaller-scale models with Group Relative Policy Optimization (GRPO) to use external tools such as zoom. The greatest benefit is obtained with a combination of GRPO learning, a simple reward structure, a simplified tool-calling interface, allocating additional tokens to the result of the tool call, and a training data mix that over-represents visually difficult examples. Compared to similarly-sized baseline models, our method achieves better performance on some visual question-answering (VQA) tasks, thanks to the detailed visual information gathered from the external tool.

[Arxiv](https://arxiv.org/abs/2506.14821)