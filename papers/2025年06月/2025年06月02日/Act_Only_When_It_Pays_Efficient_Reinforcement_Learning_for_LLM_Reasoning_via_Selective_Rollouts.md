# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年06月02日

`Agent` `人工智能` `计算优化`

> Act Only When It Pays: Efficient Reinforcement Learning for LLM Reasoning via Selective Rollouts

# 摘要

> 强化学习（如 PPO 和 GRPO）在 LLM 推理领域取得了突破性进展。通过扩大 rollout 的规模来采样更多提示，模型能够更有针对性地利用高质量数据进行训练，从而稳定强化学习过程并提升模型性能。然而，这种方法伴随着显著的计算开销。我们发现，通过在 rollout 之前跳过无信息量的提示，可以大幅减少这部分开销。通过对奖励动态的分析，我们发现提示值具有强烈的时间一致性：在某一训练周期中无信息量的提示在未来周期中也很可能保持无信息量。基于此，我们提出了 GRESO（高效选择性 rollout 的 GRPO），这是一种在线、轻量级的预-rollout 过滤算法，通过奖励训练动态预测并跳过无信息量的提示。我们在广泛的数学推理基准测试和模型（如 Qwen2.5-Math-1.5B、DeepSeek-R1-Distill-Qwen-1.5B 和 Qwen2.5-Math-7B）上进行评估，结果显示 GRESO 在 rollout 阶段实现了高达 2.4 倍的时钟时间加速，总体训练时间也提升了 2.0 倍，且未出现准确率下降。


> Reinforcement learning, such as PPO and GRPO, has powered recent breakthroughs in LLM reasoning. Scaling rollout to sample more prompts enables models to selectively use higher-quality data for training, which can stabilize RL training and improve model performance. However, this comes at the cost of significant computational overhead. In this paper, we show that a substantial portion of this overhead can be avoided by skipping uninformative prompts before rollout. Our analysis of reward dynamics reveals a strong temporal consistency in prompt value: prompts that are uninformative in one epoch of training are likely to remain uninformative in future epochs. Based on these insights, we propose GRESO (GRPO with Efficient Selective Rollout), an online, lightweight pre-rollout filtering algorithm that predicts and skips uninformative prompts using reward training dynamics. By evaluating GRESO on a broad range of math reasoning benchmarks and models, such as Qwen2.5-Math-1.5B, DeepSeek-R1-Distill-Qwen-1.5B, and Qwen2.5-Math-7B, we show that GRESO achieves up to 2.4x wall-clock time speedup in rollout and up to 2.0x speedup in total training time without accuracy degradation.

[Arxiv](https://arxiv.org/abs/2506.02177)