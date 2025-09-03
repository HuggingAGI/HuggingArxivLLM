# SimpleTIR：面向多轮工具集成推理的端到端强化学习

发布时间：2025年09月02日

`强化学习` `基础理论`

> SimpleTIR: End-to-End Reinforcement Learning for Multi-Turn Tool-Integrated Reasoning

# 摘要

> 大型语言模型（LLMs）通过与外部工具交互能显著增强推理能力，这一范式被称为工具集成推理（TIR）。然而，当使用强化学习（RL）将TIR扩展到多轮场景时，训练不稳定性和性能崩溃问题往往会成为阻碍。我们发现，这种不稳定性主要源于外部工具反馈的分布偏移，进而导致低概率标记的生成。该问题在连续轮次中不断加剧，引发灾难性的梯度范数爆炸，最终扰乱训练进程。为解决这一难题，我们提出了SimpleTIR——一种即插即用的算法，能够稳定多轮TIR训练。其核心策略是识别并过滤包含无效轮次的轨迹——所谓无效轮次，指既未生成代码块也未得出最终答案的轮次。通过在策略更新中剔除这些问题轨迹，SimpleTIR有效阻断了有害的高幅度梯度，进而稳定了学习动态。大量实验结果显示，SimpleTIR在极具挑战性的数学推理基准测试中表现卓越，创下当前最佳性能；尤其值得一提的是，以Qwen2.5-7B基础模型为起点时，它将AIME24分数从纯文本基线的22.1提升至50.5。此外，由于摆脱了监督微调的束缚，SimpleTIR还能促使模型探索出多样化的复杂推理模式，如自我修正与交叉验证等。

> Large Language Models (LLMs) can significantly improve their reasoning capabilities by interacting with external tools, a paradigm known as Tool-Integrated Reasoning (TIR). However, extending TIR to multi-turn scenarios using Reinforcement Learning (RL) is often hindered by training instability and performance collapse. We identify that such instability is primarily caused by a distributional drift from external tool feedback, leading to the generation of low-probability tokens. This issue compounds over successive turns, causing catastrophic gradient norm explosions that derail the training process. To address this challenge, we introduce SimpleTIR , a plug-and-play algorithm that stabilizes multi-turn TIR training. Its core strategy is to identify and filter out trajectories containing void turns, i.e., turns that yield neither a code block nor a final answer. By removing these problematic trajectories from the policy update, SimpleTIR effectively blocks the harmful, high-magnitude gradients, thus stabilizing the learning dynamics. Extensive experiments show that SimpleTIR achieves state-of-the-art performance on challenging math reasoning benchmarks, notably elevating the AIME24 score from a text-only baseline of 22.1 to 50.5 when starting from the Qwen2.5-7B base model. Furthermore, by avoiding the constraints of supervised fine-tuning, SimpleTIR encourages the model to discover diverse and sophisticated reasoning patterns, such as self-correction and cross-validation.

[Arxiv](https://arxiv.org/abs/2509.02479)