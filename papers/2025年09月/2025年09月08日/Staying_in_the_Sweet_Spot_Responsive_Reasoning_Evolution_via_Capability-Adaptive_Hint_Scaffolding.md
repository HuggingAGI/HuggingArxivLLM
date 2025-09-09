# 立足甜蜜点：基于能力自适应提示支架的响应式推理演进

发布时间：2025年09月08日

`强化学习` `基础理论`

> Staying in the Sweet Spot: Responsive Reasoning Evolution via Capability-Adaptive Hint Scaffolding

# 摘要

> 带可验证奖励的强化学习（RLVR）在提升大型语言模型（LLMs）推理能力方面成效显著。然而，现有RLVR方法常因训练数据难度与模型能力不匹配而探索效率欠佳：问题过难时，LLMs难以找到可行推理路径；问题过简单时，模型又几乎学不到新能力。本研究通过量化损失下降速度与滚动准确率的关系，将问题难度的影响进行了形式化定义。基于此分析，我们提出了SEELE——一种新型监督辅助RLVR框架，它能动态调整问题难度，使其始终处于高效学习区间。SEELE通过在原始问题后附加提示（完整解答的一部分）对每个训练样本进行增强。与以往基于提示的方法不同，SEELE会针对每个问题针对性地自适应调整提示长度，以实现最优难度。为确定最优提示长度，SEELE采用多轮滚动采样策略：在每一轮中，它将项目反应理论模型拟合至前几轮收集的准确率-提示数据对，进而预测下一轮所需的提示长度。这种实例级实时难度调整机制，让问题难度与模型能力的动态变化相适配，从而提升了探索效率。实验结果显示，在六个数学推理基准测试中，SEELE的表现分别超越组相对策略优化（GRPO）11.8分、监督微调（SFT）10.5分，且平均比以往最佳监督辅助方法高出3.6分。

> Reinforcement learning with verifiable rewards (RLVR) has achieved remarkable success in enhancing the reasoning capabilities of large language models (LLMs). However, existing RLVR methods often suffer from exploration inefficiency due to mismatches between the training data's difficulty and the model's capability. LLMs fail to discover viable reasoning paths when problems are overly difficult, while learning little new capability when problems are too simple. In this work, we formalize the impact of problem difficulty by quantifying the relationship between loss descent speed and rollout accuracy. Building on this analysis, we propose SEELE, a novel supervision-aided RLVR framework that dynamically adjusts problem difficulty to stay within the high-efficiency region. SEELE augments each training sample by appending a hint (part of a full solution) after the original problem. Unlike previous hint-based approaches, SEELE deliberately and adaptively adjusts the hint length for each problem to achieve an optimal difficulty. To determine the optimal hint length, SEELE employs a multi-round rollout sampling strategy. In each round, it fits an item response theory model to the accuracy-hint pairs collected in preceding rounds to predict the required hint length for the next round. This instance-level, real-time difficulty adjustment aligns problem difficulty with the evolving model capability, thereby improving exploration efficiency. Experimental results show that SEELE outperforms Group Relative Policy Optimization (GRPO) and Supervised Fine-tuning (SFT) by +11.8 and +10.5 points, respectively, and surpasses the best previous supervision-aided approach by +3.6 points on average across six math reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2509.06923)