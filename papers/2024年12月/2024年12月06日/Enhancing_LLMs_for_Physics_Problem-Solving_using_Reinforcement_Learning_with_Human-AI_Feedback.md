# 利用具有人类 - AI 反馈的强化学习来提升用于解决物理问题的大型语言模型

发布时间：2024年12月06日

`LLM应用`

> Enhancing LLMs for Physics Problem-Solving using Reinforcement Learning with Human-AI Feedback

# 摘要

> 大型语言模型（LLMs）在文本类任务中能力出众，然而在应对物理问题所需的复杂推理时却力不从心，尤其是在高级算术和概念理解方面。尽管部分研究已尝试借助提示工程和检索增强生成（RAG）等技术强化物理教育中的LLMs，但在克服其物理推理的局限性方面投入不足。本文给出一种利用具有人类和人工智能反馈的强化学习（RLHAIF）来提升LLMs处理物理问题表现的新途径。我们对几种强化学习方法进行了评估，包括近端策略优化（PPO）、直接偏好优化（DPO）和Remax优化。之所以选择这些方法，是为了探究在PhyQA数据集（其中涵盖了高中教材中的高难度物理问题）不同设置下的RL策略性能。我们的RLHAIF模型在诸如LLaMA2和Mistral等主流LLMs上进行了测试，成果斐然，特别是MISTRAL-PPO模型，在推理和准确性方面提升显著。它成绩出色，METEOR得分达58.67，推理得分0.74，为该领域未来的物理推理研究树立了优秀典范。

> Large Language Models (LLMs) have demonstrated strong capabilities in text-based tasks but struggle with the complex reasoning required for physics problems, particularly in advanced arithmetic and conceptual understanding. While some research has explored ways to enhance LLMs in physics education using techniques such as prompt engineering and Retrieval Augmentation Generation (RAG), not enough effort has been made in addressing their limitations in physics reasoning. This paper presents a novel approach to improving LLM performance on physics questions using Reinforcement Learning with Human and Artificial Intelligence Feedback (RLHAIF). We evaluate several reinforcement learning methods, including Proximal Policy Optimization (PPO), Direct Preference Optimization (DPO), and Remax optimization. These methods are chosen to investigate RL policy performance with different settings on the PhyQA dataset, which includes challenging physics problems from high school textbooks. Our RLHAIF model, tested on leading LLMs like LLaMA2 and Mistral, achieved superior results, notably with the MISTRAL-PPO model, demonstrating marked improvements in reasoning and accuracy. It achieved high scores, with a 58.67 METEOR score and a 0.74 Reasoning score, making it a strong example for future physics reasoning research in this area.

[Arxiv](https://arxiv.org/abs/2412.06827)