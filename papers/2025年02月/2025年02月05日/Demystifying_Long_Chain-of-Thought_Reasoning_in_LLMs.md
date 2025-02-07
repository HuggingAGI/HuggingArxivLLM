# 解密LLMs中的长链思维推理

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）在长链思维（CoTs）推理中的机制和训练策略，特别是通过监督微调（SFT）和强化学习（RL）来增强模型的推理能力。论文的核心内容集中在理论层面，研究了模型推理能力的发展、奖励信号的作用以及基础模型的固有能力等。这些研究为优化LLMs的训练策略提供了理论指导，因此应归类为“LLM理论”。` `人工智能`

> Demystifying Long Chain-of-Thought Reasoning in LLMs

# 摘要

> # 摘要
扩展推理计算能力显著提升了大型语言模型（LLMs）的推理能力，长链思维（CoTs）使得回溯和错误纠正等策略成为可能。强化学习（RL）已成为开发这些能力的关键方法，但长CoTs出现的条件仍不明确，且RL训练需要谨慎的设计选择。本研究系统探讨了长CoT推理的机制，识别了模型生成长CoT轨迹的关键因素。通过广泛的监督微调（SFT）和RL实验，我们得出四个主要结论：（1）SFT虽非必需，但能简化训练并提升效率；（2）推理能力随训练计算量增加而显现，但其发展并不确定，因此奖励塑造对稳定CoT长度增长至关重要；（3）扩展可验证的奖励信号对RL极为关键。我们发现，利用带有过滤机制的噪声网络提取解决方案在STEM推理等分布外（OOD）任务中表现出强大潜力；（4）基础模型固有地具备错误纠正等核心能力，但通过RL有效激励这些技能以应对复杂任务需要大量计算，且测量其出现需细致方法。这些见解为优化训练策略以增强LLMs中的长CoT推理提供了实用指导。代码可在以下网址获取：https://github.com/eddycmu/demystify-long-cot。

> Scaling inference compute enhances reasoning in large language models (LLMs), with long chains-of-thought (CoTs) enabling strategies like backtracking and error correction. Reinforcement learning (RL) has emerged as a crucial method for developing these capabilities, yet the conditions under which long CoTs emerge remain unclear, and RL training requires careful design choices. In this study, we systematically investigate the mechanics of long CoT reasoning, identifying the key factors that enable models to generate long CoT trajectories. Through extensive supervised fine-tuning (SFT) and RL experiments, we present four main findings: (1) While SFT is not strictly necessary, it simplifies training and improves efficiency; (2) Reasoning capabilities tend to emerge with increased training compute, but their development is not guaranteed, making reward shaping crucial for stabilizing CoT length growth; (3) Scaling verifiable reward signals is critical for RL. We find that leveraging noisy, web-extracted solutions with filtering mechanisms shows strong potential, particularly for out-of-distribution (OOD) tasks such as STEM reasoning; and (4) Core abilities like error correction are inherently present in base models, but incentivizing these skills effectively for complex tasks via RL demands significant compute, and measuring their emergence requires a nuanced approach. These insights provide practical guidance for optimizing training strategies to enhance long CoT reasoning in LLMs. Our code is available at: https://github.com/eddycmu/demystify-long-cot.

[Arxiv](https://arxiv.org/abs/2502.03373)