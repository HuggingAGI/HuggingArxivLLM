# 深度隐式认知助力可靠链式推理

发布时间：2025年07月14日

`LLM理论` `推理系统` `人工智能`

> Deep Hidden Cognition Facilitates Reliable Chain-of-Thought Reasoning

# 摘要

> 思维链推理（CoT）在LLMs和MLLMs中展现了卓越的深度推理能力，然而其可靠性常因中间步骤的错误累积而受到影响。本文提出了一种新颖的方法，通过利用模型内在的真实性编码来校准CoT推理的准确性。我们发现，特定的注意力头激活能够可靠地反映CoT推理步骤的真实性。基于这一发现，我们训练了一个置信度预测器，利用这些与真实性敏感的激活来评估每一步推理的正确性，并通过束搜索动态选择最合理的推理路径。实验结果表明，我们的方法在数学、符号和常识推理任务上显著超越了现有最先进基线（如 Few-Shot CoT、Self-Consistency 和 Self-Evaluation Guided Beam Search），在单模态和多模态设置中均展现出更高的准确性和可靠性。我们进一步在大型推理模型上验证了该方法，证实了其对专用推理模型的适用性。此外，我们还探讨了模型自我纠错能力在CoT推理中的作用。这项工作为CoT推理提供了一条新颖的可靠性提升路径，具有广泛的应用潜力。

> Chain of Thought (CoT) reasoning has demonstrated remarkable deep reasoning capabilities in both large language models (LLMs) and multimodal large language models (MLLMs). However, its reliability is often undermined by the accumulation of errors in intermediate steps. This paper introduces an novel approach to calibrate the CoT reasoning accuracy by leveraging the model's intrinsic veracity encoding. We discover that specific attention head activations reliably reflect the truthfulness of reasoning steps in CoT. Based on this insight, we train a confidence predictor to evaluate the correctness of each reasoning step using these truthfulness-sensitive activations, dynamically selecting the most plausible reasoning path via beam search. Experimental results demonstrate that our method significantly outperforms the state-of-the-art baselines (e.g., Few-Shot CoT, Self-Consistency, and Self-Evaluation Guided Beam Search) across the mathematical, symbolic, and commonsense reasoning tasks, exhibiting superior accuracy and reliability in both unimodal and multimodal settings. We further validate the approach on large reasoning models, confirming its applicability to specialized reasoning models. Additionally, we explore the role of the model's self-correction ability in CoT reasoning. This work provides a novel reliability improvement path for CoT reasoning with broad application potential.

[Arxiv](https://arxiv.org/abs/2507.10007)