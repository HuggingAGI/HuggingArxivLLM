# # 智能体奖励建模：融合人类偏好与可验证正确性信号，构建可靠奖励系统

发布时间：2025年02月26日

`LLM应用` `人工智能` `机器学习`

> Agentic Reward Modeling: Integrating Human Preferences with Verifiable Correctness Signals for Reliable Reward Systems

# 摘要

> 奖励模型（RMs）对大型语言模型（LLMs）的训练和推理扩展至关重要。然而，现有奖励模型主要侧重于人类偏好，忽视了在训练LLMs中表现突出潜力的可验证正确性信号。本文提出代理奖励建模方法，结合奖励模型与多维度可验证正确性信号，打造可靠奖励系统。我们开发了一个名为RewardAgent的奖励代理，整合了人类偏好奖励与事实性、指令遵循两个可验证信号，提供更可靠的奖励机制。通过在现有奖励模型基准和真实世界下游任务中进行实验和最佳n搜索，RewardAgent显著超越传统奖励模型，验证了其有效性。我们利用RewardAgent构建训练偏好对，并以DPO目标训练LLM，在NLP基准测试中展现出优于传统奖励模型的性能。我们的代码已开源，助力进一步研究（https://github.com/THU-KEG/Agentic-Reward-Modeling）。

> Reward models (RMs) are crucial for the training and inference-time scaling up of large language models (LLMs). However, existing reward models primarily focus on human preferences, neglecting verifiable correctness signals which have shown strong potential in training LLMs. In this paper, we propose agentic reward modeling, a reward system that combines reward models with verifiable correctness signals from different aspects to provide reliable rewards. We empirically implement a reward agent, named RewardAgent, that combines human preference rewards with two verifiable signals: factuality and instruction following, to provide more reliable rewards. We conduct comprehensive experiments on existing reward model benchmarks and inference time best-of-n searches on real-world downstream tasks. RewardAgent significantly outperforms vanilla reward models, demonstrating its effectiveness. We further construct training preference pairs using RewardAgent and train an LLM with the DPO objective, achieving superior performance on various NLP benchmarks compared to conventional reward models. Our codes are publicly released to facilitate further research (https://github.com/THU-KEG/Agentic-Reward-Modeling).

[Arxiv](https://arxiv.org/abs/2502.19328)