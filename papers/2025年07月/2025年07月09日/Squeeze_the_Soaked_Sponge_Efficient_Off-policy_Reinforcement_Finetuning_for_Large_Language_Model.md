# 挤干浸水海绵：大型语言模型的高效离策略强化微调

发布时间：2025年07月09日

`LLM应用` `人工智能`

> Squeeze the Soaked Sponge: Efficient Off-policy Reinforcement Finetuning for Large Language Model

# 摘要

> 强化学习（RL）在提升大型语言模型（LLMs）推理能力方面展现出巨大潜力。然而，现有强化微调（RFT）方法主要采用On-policy RL，导致过去学习生成的数据未被充分利用，这极大增加了计算和时间成本，成为经济高效扩展的瓶颈。为此，我们提出了一种名为Reincarnating Mix-policy Proximal Policy Gradient（ReMix）的方法，使PPO和GRPO等On-policy RFT方法能够利用Off-policy数据。ReMix由三部分组成：高效训练的混合策略近端策略梯度（UTD比率提升）、平衡稳定性和灵活性的KL-凸策略约束，以及实现从高效早期学习到平稳渐进改进的策略重生。实验中，我们在PPO、GRPO及1.5B、7B模型上训练了ReMix模型。在五个数学推理基准测试中，ReMix的Pass@1准确率高达52.10%（1.5B模型），仅需0.079M响应展开和350步训练；对于7B模型，准确率分别达到63.27%/64.39%，仅需0.007M/0.011M响应展开和50/75步训练。与15个先进模型对比，ReMix不仅性能领先，且将训练成本降低了30-450倍。此外，我们通过多维度分析揭示了有趣现象，如Off-policy差异的鞭笞效应导致对较短响应的偏好，以及严重Off-policyness下自我反思行为的崩溃模式等。

> Reinforcement Learning (RL) has demonstrated its potential to improve the reasoning ability of Large Language Models (LLMs). One major limitation of most existing Reinforcement Finetuning (RFT) methods is that they are on-policy RL in nature, i.e., data generated during the past learning process is not fully utilized. This inevitably comes at a significant cost of compute and time, posing a stringent bottleneck on continuing economic and efficient scaling. To this end, we launch the renaissance of off-policy RL and propose Reincarnating Mix-policy Proximal Policy Gradient (ReMix), a general approach to enable on-policy RFT methods like PPO and GRPO to leverage off-policy data. ReMix consists of three major components: (1) Mix-policy proximal policy gradient with an increased Update-To-Data (UTD) ratio for efficient training; (2) KL-Convex policy constraint to balance the trade-off between stability and flexibility; (3) Policy reincarnation to achieve a seamless transition from efficient early-stage learning to steady asymptotic improvement. In our experiments, we train a series of ReMix models upon PPO, GRPO and 1.5B, 7B base models. ReMix shows an average Pass@1 accuracy of 52.10% (for 1.5B model) with 0.079M response rollouts, 350 training steps and achieves 63.27%/64.39% (for 7B model) with 0.007M/0.011M response rollouts, 50/75 training steps, on five math reasoning benchmarks (i.e., AIME'24, AMC'23, Minerva, OlympiadBench, and MATH500). Compared with 15 recent advanced models, ReMix shows SOTA-level performance with an over 30x to 450x reduction in training cost in terms of rollout data volume. In addition, we reveal insightful findings via multifaceted analysis, including the implicit preference for shorter responses due to the Whipping Effect of off-policy discrepancy, the collapse mode of self-reflection behavior under the presence of severe off-policyness, etc.

[Arxiv](https://arxiv.org/abs/2507.06892)