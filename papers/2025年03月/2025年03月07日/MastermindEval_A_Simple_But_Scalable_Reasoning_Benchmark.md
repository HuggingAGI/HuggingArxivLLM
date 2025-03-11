# # MastermindEval：简单却可扩展的推理基准

发布时间：2025年03月07日

`LLM应用

理由：这篇论文探讨了如何评估大型语言模型的推理能力，并提出了一种新的基准测试方法。它属于应用层面，因为它关注如何应用模型进行推理任务的评估，而不是模型的理论或架构。` `人工智能`

> MastermindEval: A Simple But Scalable Reasoning Benchmark

# 摘要

> 大型语言模型（LLMs）在语言理解和数学任务中表现卓越，这促使人们对评估其推理能力产生了浓厚兴趣，推动了常识、数值、逻辑和定性推理的研究。然而，随着OpenAI的o1和DeepSeek的R1等专注于推理的模型快速发展，建立能够跟上模型进步的推理基准变得尤为重要。本文提出了一种受经典桌游Mastermind启发的简单、可扩展且易于解释的演绎推理基准——MastermindEval。该基准支持两种评估模式：(1) 智能体评估模式，模型自主完成游戏；(2) 演绎推理评估模式，模型根据已有游戏状态推断唯一可能的正确代码。实验结果表明：(1) 即使是简单的Mastermind案例，当前模型也难以应对；(2) 该基准具备良好的扩展性，未来可能适用于更先进的模型。此外，我们发现，随着需要整合信息的陈述数量增加，当前模型在推断隐藏代码方面的能力受到限制。

> Recent advancements in large language models (LLMs) have led to remarkable performance across a wide range of language understanding and mathematical tasks. As a result, increasing attention has been given to assessing the true reasoning capabilities of LLMs, driving research into commonsense, numerical, logical, and qualitative reasoning. However, with the rapid progress of reasoning-focused models such as OpenAI's o1 and DeepSeek's R1, there has been a growing demand for reasoning benchmarks that can keep pace with ongoing model developments. In this paper, we introduce MastermindEval, a simple, scalable, and interpretable deductive reasoning benchmark inspired by the board game Mastermind. Our benchmark supports two evaluation paradigms: (1) agentic evaluation, in which the model autonomously plays the game, and (2) deductive reasoning evaluation, in which the model is given a pre-played game state with only one possible valid code to infer. In our experimental results we (1) find that even easy Mastermind instances are difficult for current models and (2) demonstrate that the benchmark is scalable to possibly more advanced models in the future Furthermore, we investigate possible reasons why models cannot deduce the final solution and find that current models are limited in deducing the concealed code as the number of statement to combine information from is increasing.

[Arxiv](https://arxiv.org/abs/2503.05891)