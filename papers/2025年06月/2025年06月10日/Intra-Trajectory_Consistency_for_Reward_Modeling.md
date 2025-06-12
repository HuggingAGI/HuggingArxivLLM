# 轨迹内一致性在奖励建模中的应用

发布时间：2025年06月10日

`LLM理论`

> Intra-Trajectory Consistency for Reward Modeling

# 摘要

> 奖励模型是提升大型语言模型性能的关键，尤其在基于人类反馈的强化学习（RLHF）和推理时验证中发挥重要作用。目前的奖励建模主要通过整体响应的评分来学习结果奖励，但这种方法存在局限性。由于响应级别的评分是粗粒度的监督信号，奖励模型难以准确识别响应轨迹中真正影响评分的具体因素，导致在处理新响应时表现欠佳。

针对这一问题，我们提出了一种创新方法，利用生成概率在响应轨迹中建立奖励一致性。这种方法使响应级别的监督信号能够在过程中传递，为奖励学习提供更精细的指导。基于贝叶斯框架的分析，我们开发了一种轨迹内一致性正则化方法，确保具有更高下一个令牌生成概率的相邻过程保持一致的奖励。通过将该方法应用于先进的结果奖励模型，我们在RewardBench基准测试中取得了显著的性能提升。

此外，我们发现，采用该正则化方法训练的奖励模型不仅能够更好地与DPO策略对齐，还在最佳N选一（BON）推理时验证中表现优异。我们的代码已开源，可在GitHub仓库https://github.com/chaoyang101/ICRM中获取。


> Reward models are critical for improving large language models (LLMs), particularly in reinforcement learning from human feedback (RLHF) or inference-time verification. Current reward modeling typically relies on scores of overall responses to learn the outcome rewards for the responses. However, since the response-level scores are coarse-grained supervision signals, the reward model struggles to identify the specific components within a response trajectory that truly correlate with the scores, leading to poor generalization on unseen responses. In this paper, we propose to leverage generation probabilities to establish reward consistency between processes in the response trajectory, which allows the response-level supervisory signal to propagate across processes, thereby providing additional fine-grained signals for reward learning. Building on analysis under the Bayesian framework, we develop an intra-trajectory consistency regularization to enforce that adjacent processes with higher next-token generation probability maintain more consistent rewards. We apply the proposed regularization to the advanced outcome reward model, improving its performance on RewardBench. Besides, we show that the reward model trained with the proposed regularization induces better DPO-aligned policies and achieves better best-of-N (BON) inference-time verification results. Our code is provided in https://github.com/chaoyang101/ICRM.

[Arxiv](https://arxiv.org/abs/2506.09096)