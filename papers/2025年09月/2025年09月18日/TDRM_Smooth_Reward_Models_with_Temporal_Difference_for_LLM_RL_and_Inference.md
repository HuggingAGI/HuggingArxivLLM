# TDRM：面向大型语言模型强化学习与推理的时序差分平滑奖励模型

发布时间：2025年09月18日

`强化学习` `基础理论`

> TDRM: Smooth Reward Models with Temporal Difference for LLM RL and Inference

# 摘要

> 奖励模型是语言模型强化学习（RL）与推理时验证的核心。然而，现有奖励模型常因缺乏时间一致性，导致策略更新低效且强化学习训练不稳定。为此，我们提出TDRM方法，通过在训练中最小化时间差异来学习更平滑、可靠的奖励模型。这种时间差分（TD）正则化不仅能生成平滑奖励，还能更好地对齐长期目标。将TDRM融入演员-评论家式在线强化学习循环，可带来稳定的实证提升。值得注意的是，TDRM是可验证奖励方法的补充，二者可串联使用。实验表明，经TD训练的过程奖励模型（PRMs）在最佳N选（提升最高6.6%）和树搜索（提升最高23.7%）任务中性能显著提升；与带可验证奖励的强化学习（RLVR）结合时，TD训练的PRMs还能大幅提升数据效率——仅用2.5k数据即可达到基线方法需50.1k数据才能实现的性能，并在8个模型变体（5个系列）上生成更高质量的语言模型策略，如Qwen2.5-（0.5B、1.5B）、GLM4-9B-0414、GLM-Z1-9B-0414、Qwen2.5-Math-（1.5B、7B）及DeepSeek-R1-Distill-Qwen-（1.5B、7B）。所有代码已发布于https://github.com/THUDM/TDRM。

> Reward models are central to both reinforcement learning (RL) with language models and inference-time verification. However, existing reward models often lack temporal consistency, leading to ineffective policy updates and unstable RL training. We introduce TDRM, a method for learning smoother and more reliable reward models by minimizing temporal differences during training. This temporal-difference (TD) regularization produces smooth rewards and improves alignment with long-term objectives. Incorporating TDRM into the actor-critic style online RL loop yields consistent empirical gains. It is worth noting that TDRM is a supplement to verifiable reward methods, and both can be used in series. Experiments show that TD-trained process reward models (PRMs) improve performance across Best-of-N (up to 6.6%) and tree-search (up to 23.7%) settings. When combined with Reinforcement Learning with Verifiable Rewards (RLVR), TD-trained PRMs lead to more data-efficient RL -- achieving comparable performance with just 2.5k data to what baseline methods require 50.1k data to attain -- and yield higher-quality language model policies on 8 model variants (5 series), e.g., Qwen2.5-(0.5B, 1,5B), GLM4-9B-0414, GLM-Z1-9B-0414, Qwen2.5-Math-(1.5B, 7B), and DeepSeek-R1-Distill-Qwen-(1.5B, 7B). We release all code at https://github.com/THUDM/TDRM.

[Arxiv](https://arxiv.org/abs/2509.15110)