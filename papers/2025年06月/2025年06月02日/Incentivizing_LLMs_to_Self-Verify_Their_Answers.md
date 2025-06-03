# # 激励大型语言模型自我验证其答案

发布时间：2025年06月02日

`LLM应用` `数学推理`

> Incentivizing LLMs to Self-Verify Their Answers

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中通过训练后和测试时的缩放定律取得了显著进展。尽管常见的测试时缩放方法通常通过使用外部奖励模型来引导模型生成过程，但我们发现，当对特定推理任务进行训练后缩放时，仅能获得微乎其微的提升。我们发现，这种有限的改进源于特定训练后的生成器与通用奖励模型之间的分布差异。为了解决这一问题，我们提出了一种框架，激励LLMs自我验证自己的答案。通过将答案生成和验证统一到一个强化学习（RL）过程中，我们训练出能够有效评估自己解决方案正确性的模型。经过训练的模型可以在推理时通过验证其生成内容来进一步提升性能，而无需外部验证器。我们基于Qwen2.5-Math-7B和DeepSeek-R1-Distill-Qwen-1.5B训练了我们的自我验证模型，展示了其在不同推理上下文长度下的能力。在多个数学推理基准上的实验表明，我们的模型不仅可以提升训练后的性能，还可以实现有效的测试时缩放。我们的代码可在https://github.com/mansicer/self-verification获取。

> Large Language Models (LLMs) have demonstrated remarkable progress in complex reasoning tasks through both post-training and test-time scaling laws. While prevalent test-time scaling approaches are often realized by using external reward models to guide the model generation process, we find only marginal gains can be acquired when scaling a model post-trained on specific reasoning tasks. We identify that the limited improvement stems from distribution discrepancies between the specific post-trained generator and the general reward model. To address this, we propose a framework that incentivizes LLMs to self-verify their own answers. By unifying answer generation and verification within a single reinforcement learning (RL) process, we train models that can effectively assess the correctness of their own solutions. The trained model can further scale its performance during inference time by verifying its generations, without the need for external verifiers. We train our self-verification models based on Qwen2.5-Math-7B and DeepSeek-R1-Distill-Qwen-1.5B, demonstrating its capabilities across varying reasoning context lengths. Experiments on multiple mathematical reasoning benchmarks show that our models can not only improve post-training performance but also enable effective test-time scaling. Our code is available at https://github.com/mansicer/self-verification.

[Arxiv](https://arxiv.org/abs/2506.01369)