# DeepSeek-R1: 用强化学习激发LLM的推理潜能

发布时间：2025年01月22日

`LLM应用

理由：这篇论文介绍了DeepSeek-R1-Zero和DeepSeek-R1两个推理模型，重点在于通过强化学习（RL）和多阶段训练提升推理能力，并开源了相关模型以支持研究社区。这些内容主要涉及大型语言模型（LLM）在实际应用中的开发和优化，因此应归类为LLM应用。` `人工智能` `机器学习`

> DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning

# 摘要

> 我们推出了第一代推理模型 DeepSeek-R1-Zero 和 DeepSeek-R1。DeepSeek-R1-Zero 通过大规模强化学习（RL）训练，无需监督微调（SFT），展现了卓越的推理能力。通过 RL，DeepSeek-R1-Zero 自然涌现出许多强大且有趣的推理行为，但也面临可读性差和语言混合等挑战。为解决这些问题并进一步提升推理性能，我们推出了 DeepSeek-R1，它在 RL 前引入了多阶段训练和冷启动数据。DeepSeek-R1 在推理任务上实现了与 OpenAI-o1-1217 相当的性能。为支持研究社区，我们开源了 DeepSeek-R1-Zero、DeepSeek-R1 以及基于 Qwen 和 Llama 从 DeepSeek-R1 蒸馏出的六个密集模型（1.5B、7B、8B、14B、32B、70B）。

> We introduce our first-generation reasoning models, DeepSeek-R1-Zero and DeepSeek-R1. DeepSeek-R1-Zero, a model trained via large-scale reinforcement learning (RL) without supervised fine-tuning (SFT) as a preliminary step, demonstrates remarkable reasoning capabilities. Through RL, DeepSeek-R1-Zero naturally emerges with numerous powerful and intriguing reasoning behaviors. However, it encounters challenges such as poor readability, and language mixing. To address these issues and further enhance reasoning performance, we introduce DeepSeek-R1, which incorporates multi-stage training and cold-start data before RL. DeepSeek-R1 achieves performance comparable to OpenAI-o1-1217 on reasoning tasks. To support the research community, we open-source DeepSeek-R1-Zero, DeepSeek-R1, and six dense models (1.5B, 7B, 8B, 14B, 32B, 70B) distilled from DeepSeek-R1 based on Qwen and Llama.

[Arxiv](https://arxiv.org/abs/2501.12948)