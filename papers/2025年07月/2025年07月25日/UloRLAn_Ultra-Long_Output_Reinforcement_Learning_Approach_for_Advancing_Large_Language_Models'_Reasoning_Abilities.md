# UloRL：一种超长输出强化学习方法，用于增强大型语言模型的推理能力。

发布时间：2025年07月25日

`LLM理论` `人工智能竞赛` `人工智能`

> UloRL:An Ultra-Long Output Reinforcement Learning Approach for Advancing Large Language Models' Reasoning Abilities

# 摘要

> 大型语言模型（LLMs）的最新进展表明，可验证奖励的强化学习（RLVR）可以通过扩展输出序列显著提升模型的推理能力。然而，传统强化学习框架在处理超长输出时面临效率瓶颈，主要源于长尾序列分布和训练过程中的熵坍塌问题。为解决这些挑战，我们提出了一种超长输出强化学习（UloRL）方法，旨在突破LLMs的推理能力。具体而言，我们将超长输出解码过程分割为短片段，通过缓解长尾样本带来的训练延迟，显著提升了训练效率。同时，我们引入了动态遮蔽已掌握正向标记（MPTs）的技术，有效防止了熵坍塌现象。实验结果充分验证了我们方法的优越性。在Qwen3-30B-A3B模型上，采用分段回放策略的强化学习使训练速度提升了2.06倍。此外，支持128k-token输出的强化学习训练将模型在AIME2025任务上的准确率从70.9%提升至85.1%，在BeyondAIME任务上的准确率从50.7%提升至61.9%，甚至超越了Qwen3-235B-A22B模型，取得了显著的性能提升。这些成果凸显了我们的方法在通过超长序列生成推动LLMs推理能力发展方面的巨大潜力。我们承诺开源我们的代码和模型，为社区进一步研究提供支持。

> Recent advances in large language models (LLMs) have highlighted the potential of reinforcement learning with verifiable rewards (RLVR) to enhance reasoning capabilities through extended output sequences. However, traditional RL frameworks face inefficiencies when handling ultra-long outputs due to long-tail sequence distributions and entropy collapse during training. To address these challenges, we propose an Ultra-Long Output Reinforcement Learning (UloRL) approach for advancing large language models' reasoning abilities. Specifically, we divide ultra long output decoding into short segments, enabling efficient training by mitigating delays caused by long-tail samples. Additionally, we introduce dynamic masking of well-Mastered Positive Tokens (MPTs) to prevent entropy collapse. Experimental results demonstrate the effectiveness of our approach. On the Qwen3-30B-A3B model, RL with segment rollout achieved 2.06x increase in training speed, while RL training with 128k-token outputs improves the model's performance on AIME2025 from 70.9\% to 85.1\% and on BeyondAIME from 50.7\% to 61.9\%, even surpassing Qwen3-235B-A22B with remarkable gains. These findings underscore the potential of our methods to advance the reasoning capabilities of LLMs with ultra-long sequence generation. We will release our code and model for further use by the community.

[Arxiv](https://arxiv.org/abs/2507.19766)