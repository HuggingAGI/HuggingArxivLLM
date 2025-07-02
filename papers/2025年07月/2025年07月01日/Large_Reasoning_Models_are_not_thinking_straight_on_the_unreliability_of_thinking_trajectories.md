# 大型推理模型的思维走偏了：论思维路径的可靠性问题

发布时间：2025年07月01日

`LLM理论

理由：论文探讨了强化学习训练的大型语言模型在推理能力上的表现，特别是思维链生成的问题，属于模型理论层面的研究。` `大型语言模型`

> Large Reasoning Models are not thinking straight: on the unreliability of thinking trajectories

# 摘要

> 强化学习 (RL) 训练的大型语言模型 (LLMs) 在推理基准测试中表现优异，但研究表明这些模型常生成冗长而低效的思维链 (CoTs)，让人怀疑这些模型在推理能力上的实际提升。我们发现，这些模型存在过度思考的问题，即使面对明确提供的正确解决方案，它们仍会继续生成不必要的推理步骤，最终导致错误结论。通过在 AIME2024 数学基准测试中对三个最先进的模型进行实验，我们揭示了这些模型在整合纠正信息方面的关键性限制，这为实现稳健且可解释的推理提出了新的挑战。

> Large Language Models (LLMs) trained via Reinforcement Learning (RL) have recently achieved impressive results on reasoning benchmarks. Yet, growing evidence shows that these models often generate longer but ineffective chains of thought (CoTs), calling into question whether benchmark gains reflect real reasoning improvements. We present new evidence of overthinking, where models disregard correct solutions even when explicitly provided, instead continuing to generate unnecessary reasoning steps that often lead to incorrect conclusions. Experiments on three state-of-the-art models using the AIME2024 math benchmark reveal critical limitations in these models ability to integrate corrective information, posing new challenges for achieving robust and interpretable reasoning.

[Arxiv](https://arxiv.org/abs/2507.00711)